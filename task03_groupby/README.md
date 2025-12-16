* Task 03 – GroupBy & Tổng hợp

## Mục tiêu
Phân nhóm dữ liệu phản ánh và rút ra đặc trưng quan trọng theo area, category, department, channel.

## Dữ liệu sử dụng
- citizen_info.csv (area)
- feedback_log.csv (category, channel, department)
- resolution_time.csv (resolution_hours)

## Kết quả chính
1) area × category
Tính số lượng phản ánh theo từng area và category.

2) Theo department
Tính thời gian xử lý trung bình (resolution_hours) theo department.

3) department × category
Tính thời gian xử lý trung bình theo tổ hợp department và category.

4) Theo channel
So sánh thời gian xử lý trung bình giữa các kênh tiếp nhận.

5) Bất thường
Xác định area/department có thời gian xử lý trung bình cao bất thường (ưu tiên top 5 hoặc vượt ngưỡng).

### Kết luận
Nhận diện được nhóm xử lý chậm để ưu tiên cải thiện quy trình