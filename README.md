---
description: 本頁面內容適用的作業系統： Linux Ubuntu 24.04 LTS
---

# UCSC Genome Browser in a Box (GBiB) 繁體中文版安裝說明

## 前置作業

1. 在您的 Ubuntu 24.04 系統當中，下載並安裝 Oracle Virtual Box。\
   安裝連結：[請點我](https://www.oracle.com/tw/virtualization/technologies/vm/downloads/virtualbox-downloads.html?source=:ow:o:p:nav:mmddyyVirtualBoxHero_tw\&intcmp=:ow:o:p:nav:mmddyyVirtualBoxHero_tw)
2. 接著在 Ubuntu 24.04 系統當中，下載並安裝 Genome Browser in a Box 的虛擬機器檔案。\
   （檔案大小 > 10 GB，可能要等待超過一小時）\
   安裝連結：[請點我](https://genome-store.ucsc.edu/)
3. 將下載下來的 "gbib.zip" 解壓縮
   1. 如果您有使用者介面，請使用滑鼠右鍵點選該壓縮檔案，然後選擇 「取出」 。
   2. 或者，可以使用命令列工具，使用以下 Bash 命令來移動到您存放該壓縮檔的目錄，並解壓縮：\
      （請將 `~/Target_dir` 替換成您存放該壓縮檔的實際資料夾）
      1. 提示：可以先使用 find \~/ -type f&#x20;

<pre class="language-bash"><code class="lang-bash"><strong>cd ~/Target_dir
</strong><strong>unzip gbib.zip
</strong></code></pre>

