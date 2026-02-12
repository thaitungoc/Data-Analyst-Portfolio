# DATA ANALYST PORTFOLIO - THÁI TÚ NGỌC

Chào mừng bạn đến với Portfolio của tôi. Đây là tập hợp các dự án phân tích dữ liệu thực tế, tập trung vào kỹ năng **Kiểm soát dữ liệu (Data Integrity)** và **Phát hiện bất thường (Anomaly Detection)** 

## 1. Phân tích Hiệu Suất Chuỗi Cửa Hàng & Hub [SQL]
**Dữ liệu:** Hệ thống giao nhận (Orders, Hubs, Shippers, Stores).

- **Đối soát doanh thu:** Sử dụng `Window Functions` (`LEAD`, `RANK`) để tính chênh lệch doanh số giữa các Hub xếp hạng kế tiếp.
- **Kiểm soát hiệu suất:** Tính toán `hours_diff` để phân loại Shipper (Outperform/Late), giúp xác định các điểm nghẽn vận hành.
- **Tính toán tỷ trọng:** Phân tích cơ cấu doanh thu theo từng Hub/Thành phố.

> [🔗 Xem chi tiết mã nguồn SQL tại đây](./SQL_K309_Analysis.sql)

---

##  2. Phân tích Gian lận & Dữ liệu Y tế [Python]
**Dữ liệu:** Giao dịch tài chính (Fraud Detection) và Chỉ số sức khỏe (Diabetes).

- **Data Integrity:** Sử dụng `Pandas` để kiểm tra Null, trùng lặp và định dạng dữ liệu.
- **Anomaly Detection:** Vẽ biểu đồ `Boxplot` để xác định các giao dịch có giá trị ngoại lai bất thường.
- **Phát hiện lỗi logic:** Xác định các bản ghi có chỉ số bằng 0 (vô lý về mặt y tế) và đề xuất hướng xử lý.
- **Analysis:** Xác định khung giờ cao điểm phát sinh gian lận (Câu 3.6).
<img width="851" height="396" alt="Ảnh màn hình 2026-02-12 lúc 18 10 53" src="https://github.com/user-attachments/assets/f612bde8-c943-477d-99df-37f2b41d3248" />
Phân tích số lượt giao dịch gian lận theo thời gian (ngày qua ngày - Câu 3.5)
<img width="895" height="467" alt="Ảnh màn hình 2026-02-12 lúc 18 09 44" src="https://github.com/user-attachments/assets/f6345d5f-37bf-4934-92e4-fa3c2423d0bd" />
So sánh phân bố Glucose giữa nhóm mắc tiểu đường và không mắc tiểu đường (Câu 4.3).
<img width="623" height="449" alt="Ảnh màn hình 2026-02-12 lúc 18 12 02" src="https://github.com/user-attachments/assets/e0a71656-5db9-4ffb-b468-f1da7e06fe43" />

> [🔗 Xem chi tiết Notebook Python tại đây](./Fraud_Detection_and_Medical_Analysis.ipynb)

---

## Công cụ sử dụng
- **Ngôn ngữ:** SQL (BigQuery/Standard SQL), Python.
- **Thư viện:** Pandas, Matplotlib, Seaborn.
- **Tư duy:** Data Auditing, EDA, Statistical Analysis.
