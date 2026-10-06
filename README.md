# 張凱傑

國立中正大學資訊工程研究所畢業，使用 Python、PyTorch 與 Hugging Face Transformers 進行 NLP multi-label classification 研究。

希望應徵 **Server Software、Python Automation、系統整合與 AI／Cloud Infrastructure** 相關的初階職位。

## 代表作品

### [CVE-to-MITRE ATT&CK Techniques Mapping with SecureBERT](https://github.com/AJie913/cve-to-attack-securebert)

將 CVE 描述對應至 31 個 MITRE ATT&CK techniques 標籤，並在一致的評估流程下比較 SciBERT、SecBERT 與 SecureBERT。

- **資料處理：** 檢查重複的 CVE ID，移除 train / validation / test split 之間的重疊。
- **模型實驗：** 比較 loss function、classifier head、訓練策略與 threshold。
- **評估成果：** 在所比較的實驗流程中，SecureBERT 的 test split Weighted F1 從 **39.43% 提升至 49.22%**，增加 **9.79 個百分點**。結果來自固定 random seed 42 的實驗。
- **成果紀錄：** 提供包含執行結果的 Jupyter Notebook、實驗設定、圖表與研究限制說明。

[專案介紹與結果](https://github.com/AJie913/cve-to-attack-securebert#主要結果) · [訓練實驗 Jupyter Notebook](https://github.com/AJie913/cve-to-attack-securebert/blob/main/cve2tech/securebert/standard/ablation/exp03_training_strategy_multi_label_securebert.ipynb)

## 作品呈現的能力

| 領域 | 實作內容 |
|---|---|
| Python／PyTorch | 資料處理、模型定義、訓練與評估 |
| Transformer／NLP | 對三種 pretrained encoder 進行 fine-tuning 與比較 |
| 實驗設計 | 控制變因、逐步比較與 threshold 分析 |
| 評估與驗證 | 檢查 CVE ID 重疊、分析 multi-label classification 指標，並說明結果限制 |

## 求職方向

希望將目前的 Python、資料處理與模型實驗經驗，延伸至 **Server Software、Python Automation、系統整合與 AI／Cloud Infrastructure** 相關工作。

目前公開作品主要呈現研究與模型實驗能力，可透過專案中的程式、實驗結果與說明查看實作內容。

## 相關連結

[研究專案](https://github.com/AJie913/cve-to-attack-securebert) · [GitHub 個人首頁](https://github.com/AJie913)
