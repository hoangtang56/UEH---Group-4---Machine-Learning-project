# UEH---Group-4---Machine-Learning-project
Dự án phân tích chuỗi thời gian và dự báo bằng mô hình ARIMA theo quy trình Box-Jenkins, áp dụng Rolling Forecast và so sánh hiệu năng với Random Forest.
# 📈 Time Series Analysis & Forecasting with ARIMA

Dự án nghiên cứu, xây dựng và đánh giá mô hình dự báo chuỗi thời gian sử dụng phương pháp luận **Box-Jenkins (ARIMA)** kết hợp kỹ thuật **Rolling Forecast**, đồng thời so sánh hiệu năng với thuật toán học máy (**Random Forest**).

---

## 👥 Thành viên thực hiện
* **Giảng viên:** TS. Nguyễn An Tế
* **Danh sách nhóm:**
  1. TĂNG GIA HOÀNG
  2. PHAN THỊ VÂN DUYÊN
  3. NGUYỄN LÊ CẨM GIANG
  4. CHÂU GIA HÒA
  5. NGUYỄN THỊ THÙY DƯƠNG
* **Chuyên ngành:** Khoa học Dữ liệu
* **Khóa:** K49



---

## 🔍 Giới thiệu
Mục tiêu của dự án là triển khai toàn diện quy trình phân tích và dự báo chuỗi thời gian thực tế:
- Tiền xử lý dữ liệu (Xử lý missing values, chuẩn hóa định dạng thời gian, phân tích khám phá EDA).
- Kiểm định tính dừng (Stationarity) bằng Augmented Dickey-Fuller (ADF test) và xử lý sai phân $d$.
- Nhận dạng bậc mô hình $(p, d, q)$ qua đồ thị tự tương quan (ACF) và tự tương quan riêng phần (PACF).
- Huấn luyện hai cấu hình mô hình gồm **ARIMA(2, 0, 3)** và **ARIMA(1, 0, 0)** áp dụng kỹ thuật **Rolling Forecast**.
- Đánh giá và đối chuẩn (Benchmarking) hiệu năng giữa các mô hình ARIMA và mô hình hồi quy **Random Forest** thông qua các chỉ số RMSE, MAE, MAPE.
- Thực hiện dự báo đa bước (Multi-step forecasting) cho **365 ngày tiếp theo**.

---
