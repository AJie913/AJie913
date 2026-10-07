# 張凱傑 | Chang Kai Chieh

國立中正大學資訊工程碩士，研究使用 Python、pandas、PyTorch 與 Hugging Face Transformers 進行資料整理、模型 fine-tuning 及實驗分析，另有技術文件整合與團隊硬體專題經驗，希望投入 AI Server/Cloud Infrastructure 初階軟體與系統職務，參與自動化、驗證、整合及效能分析。

Computer science master's graduate from National Chung Cheng University with Python data processing, NLP model experimentation, and technical documentation experience, seeking entry-level software or systems roles in AI server/cloud infrastructure involving automation, validation, integration, and performance analysis.

## 研究作品

### [CVE-to-MITRE ATT&CK Mapping with SecureBERT](https://github.com/AJie913/cve-to-attack-securebert)

碩士論文研究將 CVE 描述映射至 MITRE ATT&CK techniques，以 PyTorch 與 Hugging Face Transformers 比較 SciBERT、SecBERT 與 SecureBERT，並分析 Focal Loss、MLP classifier head、訓練策略及 threshold 設定。

- **資料處理：** 使用 Python 與 pandas 依 CVE-ID 去重、排除跨集合重疊，整理 1,089 筆 training、255 筆 validation 與 317 筆 test 資料。
- **模型比較：** 在相同資料切分下比較三種 encoder，分析固定 threshold 0.5 與 adaptive thresholds 對 weighted precision、weighted recall 與 weighted F1 的影響。
- **實驗紀錄：** 公開專案提供核心 notebooks、保留輸出、實驗設定與圖表，供讀者查看研究流程。
- **評估流程：** 依 validation 結果調整參數、架構及選擇最佳 checkpoint，設定確定後以 test set 進行最終評估。

Parameter tuning, architecture changes, and checkpoint selection were based on validation results, with the test set used for final evaluation after the settings were determined.

[專案介紹](https://github.com/AJie913/cve-to-attack-securebert) · [SecureBERT 實驗 Notebook](https://github.com/AJie913/cve-to-attack-securebert/blob/main/cve2tech/securebert/standard/ablation/exp03_training_strategy_multi_label_securebert.ipynb)

## 其他專案經驗

**主動式資安防禦 | 國防科技研究計畫**

規劃系統規格與設計兩份文件的架構及章節，彙整開發成員提供的技術內容與修訂，整理文字、格式並完成定稿，文件已正式交付。

**SolarPower 車載能源管理平台 | 行動通訊實務競賽**

參與實體接線與組裝，並與團隊討論修改依電壓與設備功耗切換供電來源的控制程式，團隊作品整合 Raspberry Pi、ESP8266、電流感測器及繼電器，晉級 2024 行動通訊實務競賽智慧節能與物聯網應用組決賽。

## 研究中使用的工具與方法

- **程式與資料處理：** Python、pandas、CVE-ID 去重與跨集合重疊檢查
- **研究使用工具：** PyTorch、Hugging Face Transformers
- **模型與評估：** Multi-label classification、Transformer fine-tuning、Focal Loss、MLP classifier head、threshold 分析、weighted metrics

研究初期曾使用 LangChain 探索 LLM 與 RAG，後續以 supervised Transformer 模型完成主要研究。

## 求職方向

目前希望投入 AI Server/Cloud Infrastructure 初階軟體與系統職務，涵蓋 Python 開發、自動化、驗證、整合及效能分析，公開作品主要呈現資料處理、模型實驗與研究紀錄整理經驗。

[GitHub 個人首頁](https://github.com/AJie913)
