# Personal Electricity Cost Prediction

Đồ án sử dụng Machine Learning để dự báo lượng điện tiêu thụ và chi phí hóa đơn cho 3 tháng tiếp theo dựa trên dữ liệu lịch sử và nhiệt độ môi trường.

## Tính năng chính
- Xử lý dữ liệu chuỗi thời gian (Time Series).
- Dự báo chỉ số kWh bằng mô hình Linear Regression.
- Tự động tính toán số tiền dựa trên biểu giá điện bậc thang của EVN.

## Cách sử dụng
1. Cài đặt thư viện: `pip install -r requirements.txt`
2. Cập nhật dữ liệu cá nhân của bạn vào file `electricity_usage.csv`.
3. Chạy mã nguồn: `python predict.py`

## Kết quả
Mô hình sẽ tạo ra file `prediction_chart.png` trực quan hóa xu hướng tiêu thụ điện.
