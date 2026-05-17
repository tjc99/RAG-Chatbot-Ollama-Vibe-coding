
# 🤖 本地隱私安全 PDF 智慧對話機器人 (Ollama + Llama 3.2)

這是一個基於 **Gradio**、**FAISS 向量資料庫** 和 **Ollama (Llama 3.2)** 建構的完全本地化 RAG (檢索增強生成) 問答機器人。
所有的 PDF 解析、向量計算和大模型推理**完全在您本機運行**，0 流量消耗，100% 隱私安全。

---

## 🛠️ 前置準備

由於本項目完全在本地運行，請在啟動前確保：
1. **安裝 Ollama**：前往 [Ollama 官網](https://ollama.com/) 下載並安裝對應系統的客戶端。
2. **下載 Llama 3.2 模型**：打開電腦的終端機 (Terminal) 或命令提示字元 (CMD)，執行以下命令下載並啟動本地模型：
   ```bash
   ollama run llama3.2

3. **保持 Ollama 後台運行**。

---

## 🚀 快速開始

### 1. 克隆倉庫與進入目錄

打開終端機，執行以下命令：

```bash
git clone [https://github.com/tjc99/RAG-Chatbot-Ollama-Vibe-coding.git](https://github.com/tjc99/RAG-Chatbot-Ollama-Vibe-coding.git)
cd RAG-Chatbot-Ollama-Vibe-coding

```

### 2. 安裝 Python 依賴

建議在 Anaconda 或虛擬環境下運行：

```bash
pip install -r requirements.txt

```

### 3. 啟動應用

執行以下命令啟動 Gradio 網頁端：

```bash
python Local_Ollama_RAG.ipynb

```

程式會自動在瀏覽器中打開互動介面（預設網址為 `http://127.0.0.1:7860`）。

---

## ⚙️ 使用說明

1. **上傳檔案**：在左側欄上傳您的 **PDF 文件**。
2. **解析文件**：點擊 **「🔥 開始解析 PDF」** 按鈕，系統會將長文本切分為知識碎片並進行本地向量化。
3. **開始對話**：
> 💡 **提示**：等待系統處理狀態顯示「成功」後，即可在右側聊天介面輸入任何針對該文件的問題！



```

```
