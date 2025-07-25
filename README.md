本專案為自動化交易策略展示作品，基於 MT5 平台開發，採用 Supertrend × EMA 濾網進行多空辨識，結合固定手數與止盈止損機制，並搭配回測報表與策略筆記供審閱。

---

## 🔧 策略架構

- Supertrend 趨勢辨識
- EMA 多周期濾網（9、14、21）
- 固定手數開倉（0.5 lots）
- 止盈 60 / 止損 40 點
- 最大浮虧限制（Daily Drawdown 控制）

---

## 📈 回測報表與範例檔案

- `AlphaOverdrive_Demo.mq5`: 策略主程式
- `/report`: 包含範例回測報告（含交易明細）
- `/docs/strategy_notes.md`: 策略設計思路與參數解說
- `README.md`: 本說明文件

---

## 📌 備註

本專案僅為 **展示用途**，策略核心架構仍屬個人研發財產，**不對外提供完整邏輯與實盤參數**。如需技術合作或展示用途，歡迎私訊聯繫。
