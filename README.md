OpenAerialMap (OAM).Taiwan
===

## 什麼是 OpenAerialMap.Taiwan?
本開源計畫於 2022.11.2 啟動，預計將開源的 OpenAerialMap 在台灣建立獨立的服務。並增加各種機器學習的地圖影像辨識功能，目前正在執行中。您可以觀看我們執行的現況。來自衛星、無人機 (UAV) 和其他飛機的圖像在災難發生後變得越來越容易獲得。通常很難確定可用的內容並輕鬆讀取。 OpenAerialMap (OAM) 旨在通過提供一種簡單的開放方式來託管和提供圖像以用於人道主義響應和備災，從而解決這個問題。
## Repositories 

The following repositories are part of the OAM project:

| | |
| --- | --- |
| [oam-api](https://github.com/hotosm/oam-api) | 用於索引開放圖像的目錄 | 
| [oam-browser](https://github.com/hotosm/oam-browser) | 用於搜索可用圖像的圖像瀏覽器 |
| [oam-uploader](https://github.com/hotosm/oam-uploader) | OAM Uploader API 的 Web 前端 |
| [oam-uploader-api](https://github.com/hotosm/oam-uploader-api) | OAM 上傳器 API 服務器 |
| [oam-docs](https://github.com/hotosm/oam-docs) | OAM 文檔 |
| [openaerialmap.org](https://github.com/hotosm/openaerialmap.org) | OpenAerialMap.org 網站的程式碼 |
| [oam-design-system](https://github.com/hotosm/oam-design-system) |風格指南和 UI 組件庫 |


在 HOT Github 之外維護的存儲庫:

| | |
| --- | --- |
| [marblecutter-openaerialmap](https://github.com/mojodna/marblecutter-openaerialmap) | 用於 S3 託管的 GeoTIFF 的基於 Python、Flask 和 Lambda 的動態切片器 |
| [oam-qgis-plugin](https://github.com/yojiyojiyoji/oam_qgis3_express) | 一個實驗性的插件使 QGIS v3 連接到 OAM |


### Deprecated repositories

| | |
| --- | --- |
| [oam-server](https://github.com/hotosm/oam-server) | Main repository for imagery processing and tile service creation tools |
| [oam-server-tiler](https://github.com/hotosm/oam-server-tiler) | OAM Server tile engine |
| [oam-server-activities](https://github.com/hotosm/oam-server-activities) | SWFR Activities component for OAM Server |
| [oam-server-decider](https://github.com/hotosm/oam-server-decider) | SWF Decider component of OAM Server (using oam-server-tiler instead) |
| [oam-server-api](https://github.com/hotosm/oam-server-api) | OAM Server API |
| [oam-server-cli](https://github.com/hotosm/oam-server-cli) | A command line utility for interacting with the OAM Server API |
| [oam-server-deployment](https://github.com/hotosm/oam-server-deployment) | Amazon Web Services deployment tooling OAM Server |
| [oam-server-publisher](https://github.com/hotosm/oam-server-publisher) | Status publishing component of OAM Server |
| [oam-catalog-grid](https://github.com/hotosm/oam-catalog-grid) | Generate a vector tile grid from the OAM catalog |
| [oam-browser-filters](https://github.com/hotosm/oam-browser-filters) | The grid filters used by the oam-browser front end |
| [oam-uploader-admin](https://github.com/hotosm/oam-uploader-admin) | OAM uploader admin interface |
| [oam-status](https://github.com/hotosm/oam-status) | A simple status dashboard for oam-catalog |
| [oam-dynamic-tiler](https://github.com/hotosm/oam-dynamic-tiler) | Python, Flask and Lambda-based dynamic tiler for S3-hosted GeoTIFFs
| [oam-qgis-plugin](https://github.com/hotosm/oam-qgis-plugin) | An experimental plugin for QGIS to access OAM |

## Getting Involved

有很多方法可以參與 OpenAerialMap！首先，如果您是該項目的新手，並且想了解更多關於其當前設計和架構的信息，請查看[docs](http://docs.openaerialmap.org/)以獲得概述。

### Ideas, Issue and Discussions

討論 OpenAerialMap 的最佳地方主要在[issue tracker](https://github.com/hotosm/OpenAerialMap/issues)或上面列出的方法。

關於該項目的正在進行和過去的對話發生在項目的 [Gitter](https://gitter.im/hotosm/OpenAerialMap?) 聊天室中，並且定期更新在 [OAM-Talk mailing
list](https://groups.google.com/a/hotosm.org/forum/#!forum/openaerialmap).)中發布。

歡迎加入討論和分享你的想法!
[![Join the chat at https://gitter.im/hotosm/OpenAerialMap](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/hotosm/OpenAerialMap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  
