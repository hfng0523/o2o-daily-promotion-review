# O2O Daily Promotion Review Dashboard

O2O 每日推廣表現 Review Dashboard（v2.6）。

## 功能
- 7 個 promotion tab（星期一生果 / 星期二凍貨 / 星期三冷凍 / 星期二糧油雜貨 / 星期四 VIP / 星期五急凍 / 長者會）
- 每個 tab 有 **Daily Promotion Review（Excel 格式）**：
  - 表 A：Before / 每週 / Avg.
  - 表 B：Promotion 日 vs Normal Weekdays
- 可自訂 widget（大小 / 顯示 / 拖動排序 / 指標選擇）
- 輸出 Excel（8 sheets，含顏色同數字格式）/ 輸出 Raw CSV

## 保安
- 全頁數據以 **AES-GCM 256-bit + PBKDF2-SHA256（200,000 iterations）** 加密
- 冇密碼 = 只見到密文，睇唔到任何銷售數據
- 密碼由 HKTVmall O2O Marketing 團隊保管

## 更新
`python3 work/make_locked_v26.py` → `python3 work/deploy_v26.py`
