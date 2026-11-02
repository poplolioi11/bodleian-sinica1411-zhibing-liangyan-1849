# 資料字典

book.json是本包固定文字主本。dataset_id為作品資料集ID；version為本資料版號；source為底本、版別與歷史題署；quality為覆核狀態；metrics為本固定稿實際計數；methods為高層處理與排除說明。

pages[]依官方影像順序列出f01–f10，這裡的page_id是影像幀，不等於物理面或葉。index從1起算；canvas_id及image_url對應官方來源；source_sha256是實際固定下載影像的SHA-256；width／height是固定影像尺寸。layout_note是現代版面描述；layout_reviewed只表示完成AI版面盤點，不是人工校讀。layer_states分列文字及後加標記的處理狀態。

units[]的id保留pXX-cXX，pXX指內頁物理面，cXX是固定初稿的欄文／標題單位序號；印頁碼另用pXX-printed-page-number。陣列順序就是固定讀序。layer固定original-print；role分title、body、colophon、printed-page-number。side指在全幅影像的left或right；text是固定字串；bbox為null，不提供虛構欄或逐字座標。原初稿的order由陣列順序無損表示。

uncertainties[]每筆含id、unit_id、start、end、surface、reason、cause、extent及candidates。start／end採Unicode碼點0起算半開區間[start,end)，surface須逐字等於text[start:end]；本版extent為known，僅指位置明確，不代表讀法已核定。候選不自動替換正文。uncertainties.json將各影像幀疑讀展平並保留page_id。

source-pages.json的canvases[]與book.json的pages[]一一對應；manifest_sha256固定來源manifest，image_sha256固定下載影像；manifest_width／manifest_height是館方manifest原尺寸。images_redistributed=false明示本包不含影像。

codepoints包含欄內U+3000與原刻點號，不是純漢字數。無疑讀紀錄不代表逐字確定。任何未處理或編碼未完內容均不得以□偽裝完成；若出現□，須配合具體疑讀／缺損說明。
