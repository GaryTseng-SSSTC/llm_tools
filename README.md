# LLM工具專案

## 專案概述

這個專案提供了關於大型語言模型(LLM)部署、工具比較和企業級實作的一系列指南。透過靜態HTML頁面呈現，匯集了對不同LLM工具的深入解析與實踐經驗。

## 內容說明

本專案包含以下核心內容：

- **vLLM安裝與部署指南**：詳細說明如何設置和部署vLLM，一個高效能的大型語言模型推理引擎。
- **LLM工具比較**：深入分析vLLM、Ollama和LM Studio等不同LLM框架與工具的性能、功能和使用場景。
- **企業級本地LLM部署指南**：全面評估建構企業級本地部署(on-premise)大型語言模型運行環境，包括基礎設施、安全性、成本、運維等多方面考量。

## 頁面導覽

- `index.html` - 專案主頁，提供所有指南的集中入口
- `vLLM_Setup.html` / `vLLM_Setup2.html` - vLLM的安裝與部署指南
- `llm_tool_compa.html` - LLM工具比較分析
- `build_onpremise_llm.html` - 企業級本地LLM部署完整指南

## 目標使用者

- 數據科學家與機器學習工程師
- MLOps和DevOps專業人員
- 企業IT決策者與架構師
- 對大型語言模型部署感興趣的技術愛好者

## 啟動方式

直接在瀏覽器中開啟`index.html`即可瀏覽所有內容。或使用任何HTTP伺服器提供這些靜態文件：

```bash
# 使用Python內建HTTP伺服器（Python 3）
python -m http.server

# 使用npm serve（需先安裝：npm install -g serve）
serve
```

## 作者

Gary Tseng

## 授權

© 2025 LLM工具專案