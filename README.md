# 治病良言 · Bodleian Sinica 1411

## 摘要 / Abstract

本資料以牛津大學 Bodleian Libraries 藏 Sinica 1411《治病良言》（1849，香港英華書院印刷）為底本，供醫學史原文檢索、來源定位、引用及後續校訂。v0.2.0 比較獨立 AI 讀稿與初錄，再作非盲回圖修訂，涵蓋 10 幅影像中的 12 個原印文字面，共 81 單位、1,253 個 Unicode 碼點。22 欄字串經修訂，仍保留兩處字形對碼疑義；公開 TXT、JSON、TEI XML 與逐處訂正。修訂數量不代表錯字數或準確率，亦未經人類全文雙校。

This dataset supports medical-history discovery, source location, citation and further collation of Zhi bing liang yan (1849, printed at the Anglo-Chinese College in Hong Kong), Bodleian Libraries Sinica 1411. Version 0.2.0 compares independent AI readings with the initial transcription and applies non-blind source-image revision. It covers 12 original-print text faces across ten frames, comprising 81 units and 1,253 Unicode code points. Strings in 22 columns were revised; two glyph-to-code-point uncertainties remain. Public TXT, JSON, TEI XML and unit-level corrections document the result. Change counts are not error or accuracy estimates, and no human double collation has been performed.

**公開狀態（2026-11-02）**：[v0.2.0](https://doi.org/10.5281/zenodo.23873571)已正式發布，DOI已登記；兩平台8個下載檔的匿名比對均一致。以下固定封存說明中的「預留／製備時」記錄打包當下狀態。

**v0.2.0｜獨立AI讀稿、差異比較與非盲回圖裁定；保留2筆寕／寧未解疑讀。**

整理者：曲宸宇（Chu, Chen-Yu；GitHub：poplolioi11；[ORCID](https://orcid.org/0009-0003-9738-6914)）。本輪為1849年香港醫館文獻《治病良言》的數位化與資料上架準備，提供原文檢索、定位、引用及後續校訂；未進行生物研究、實驗或現代操作指引整理，未驗證歷史醫館自述、數字或醫療主張。

初錄先固定並公開，再比較獨立AI讀稿。主代理見過初錄與獨立稿後回固定影像裁定，屬非盲覆核。固定範圍為75個欄文／題署與6個印頁碼，合計81單位、1253個Unicode碼點。38個分歧單位已完成回圖處理，另對原先一致讀作「然後寧費錢」的p11-c02進行寧／寕字形對碼覆核，暫錄「然後寕費錢」並保留疑讀；共39項來源裁定。22個單位字串改動，不等於22個錯字或已證實成功修正數。

原獨立讀稿實際為79單位，漏列p03及p05印頁碼；另行補讀取得兩個頁碼，未回改原獨立稿。不宣稱獨立初稿完全無漏錄。初錄5筆疑讀已有具體回圖處理，另保留p11-c01與p11-c02兩處寕／寧字形對碼疑義。

底本仍為10幅官方影像幀、14內頁物理面；12面有歷史原印字，正文層p03–p12共10面。p02透印不重錄；p14印刷邊框、欄線及褐色不清痕跡性質未核，不當空白或附記完成。封面及後加館藏標記只描述。題頁載道光二十九年及香港英華書院印刷；末題署「黃泥涌仁施醫館謹白」，未另推定個人作者。

- [TXT](book.txt)、[JSON](book.json)、[TEI](book.tei.xml)、[疑讀](uncertainties.json)、[來源](source-pages.json)。
- [逐處訂正](CORRECTIONS.json)、[訂正讀法](CORRECTIONS.md)、[校讀範圍](COLLATION.md)、[品質與貢獻](QUALITY-AND-CONTRIBUTIONS.md)。
- [字典](DATA-DICTIONARY.md)、[讀者指南](READING-GUIDE.md)、[文字政策](TRANSCRIPTION-POLICY.md)、[格式驗證](VALIDATION.json)、[權利](RIGHTS.md)、[引用](CITATION.cff)。

獨立AI實際模型為gemini-3.8-flash-high；主代理及批判覆核代理的實際細分型號未獲執行環境證實，保持null。未做人類雙校、專家審定、同儕審查或準確率量測。AI一致、格式驗證與DOI均不證明文字無誤。詳細方法、程式、提示、影像裁片及完整私人紀錄未公開，未提供從影像完整重跑方法。

初錄[v0.1.0](https://doi.org/10.5281/zenodo.23872791)及其tag、固定檔與校驗值保留。系列DOI為https://doi.org/10.5281/zenodo.23872790。本版 DOI 已預留；本包建立時尚未確認正式發布或公開登記。候選包不表示新版已發布；以平台公開讀回為準。

2026-11-02有限題名及公開索引查重未找到可直接使用的本件完整文字／OCR／TEI／現代點校，不宣稱全球首錄。

## English summary

Version 0.2.0 compares independent AI reading with the frozen first transcription, followed by non-blind controller source-image adjudication. Thirty-eight difference units received source decisions. An additional review of the agreed reading in p11-c02 concerned the 寧/寕 glyph encoding: 寕 was provisionally retained with an unresolved encoding question. Twenty-two unit strings changed; two located 寕/寧 encoding uncertainties remain. The independent original omitted two printed folios, later read separately; its original output is preserved. No human double collation, expert review, peer review or measured accuracy is claimed. This is historical-document digitization and publication, without biological research, experiments or a modern procedural guide.

Keywords: 治病良言; Sinica 1411; 醫學史; 醫療慈善史; 傳教醫療史; 香港; 醫療費用話語; 英華書院; history of medicine; medical charity; medical missions history; Hong Kong; medical fees discourse; Chinese print culture; 1849; digital humanities; TEI XML.

預留版本 DOI（reserved；尚未確認正式發布）： https://doi.org/10.5281/zenodo.23873571
