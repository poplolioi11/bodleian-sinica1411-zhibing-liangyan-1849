# 讀者指南

先由book.txt閱讀；每段前的〔unit:pXX-cXX〕為現代導航標籤，段間換行不是新增古籍句讀。引文請記固定版本及unit ID。

JSON／TEI與TXT採同一固定原文字串。由unit ID的pXX與side辨明物理面，再由所屬pages[].page_id（fXX）、canvas_id及image_url開啟官方全幅影像。bbox為null，僅能定位到影像幀、左右面與單位讀序；不宣稱提供逐字影像座標。

疑讀須與uncertainties.json一起閱讀：start／end按Unicode碼點0起算，而非UTF-8 bytes、字形群或1起算字數；候選及理由只提供核查入口。疑讀仍保留原初錄正文，不因資料結構完整就算裁定完成。

敬稱欄內間隔以一個U+3000表示有間隔，不保證對應原物理寬度；行首縮排記layout_note。原刻小斜點用U+3001，不視為現代新增標點。框線、魚尾與後加館藏標記不混入正文。

本TEI是固定JSON的最小P5投影：每幅影像為div／surface，原文單位為ab，疑讀以note與旁附檔連結。它未提供完整校勘apparatus、ODD或Schematron。具體XML、Relax NG、字串往返及CFF檢查狀態看VALIDATION.json；格式通過不代表讀字正確。詳細私人流程未公開，這個包不能從原圖完整重跑。
