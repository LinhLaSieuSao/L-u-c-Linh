# Chạy thử giao diện với hồ sơ Data Analyst tổng hợp

Ngày chạy: 27/10/2026. Ảnh chụp từ ứng dụng Streamlit tại `http://127.0.0.1:8501`, kích thước khung nhìn 903 × 524 px. Đây là dữ liệu giả lập, không mô tả người thật. Mỗi ảnh ghi lại một phần đang nhìn thấy trên trang; cuộn trong ứng dụng để xem đầy đủ nội dung.

## Dữ liệu đã nhập

| Mục | Dữ liệu demo |
| --- | --- |
| Kỹ năng | SQL, Python, Excel, Power BI |
| Sở thích nghề nghiệp | Phân tích dữ liệu, trực quan hóa dữ liệu, tìm hiểu hành vi khách hàng |
| Hoạt động yêu thích | Tìm quy luật và phân tích số liệu; Tìm hiểu hành vi và nhu cầu người dùng |
| Kinh nghiệm | Thực tập phân tích dữ liệu bán lẻ: dùng SQL tổng hợp doanh thu, Excel đối chiếu số liệu và Power BI xây dashboard. |
| CV dán | Hồ sơ demo Data Analyst gồm SQL, Python/pandas, Excel, Power BI, xử lý dữ liệu thiếu và dashboard doanh thu trên dữ liệu giả lập. |
| Vị trí quan tâm | Chuyên viên phân tích dữ liệu · Data Analyst |
| JD đối chiếu | Bắt buộc: SQL, Python, Excel, Power BI. Ưu tiên: Tableau, Thống kê, Giao tiếp. |

## Từng bước trên giao diện

### 1. Mở biểu mẫu hồ sơ

![Biểu mẫu hồ sơ ban đầu](screenshots/demo-walkthrough/01-empty-profile.jpg)

### 2. Điền toàn bộ đầu vào

Đã nhập kỹ năng, sở thích, hai hoạt động yêu thích, kinh nghiệm, CV dán, vị trí và JD. Ảnh cho thấy phần vị trí và JD; xem bảng trên để đối chiếu các ô phía trên.

![Vị trí và JD đã nhập](screenshots/demo-walkthrough/02-filled-profile.jpg)

### 3. Rà soát kỹ năng trích từ CV

Ứng dụng nhận diện 6 kỹ năng: Excel, pandas, phân tích dữ liệu, Power BI, Python, SQL.

![Kỹ năng trước khi khai báo Level](screenshots/demo-walkthrough/03-review-unset-levels.jpg)

### 4. Khai báo Level và rà soát JD

SQL, Python, Excel và phân tích dữ liệu ở Level 2; Power BI và pandas ở Level 1. JD nhận diện 4 kỹ năng bắt buộc và 3 kỹ năng ưu tiên.

![Level đã chọn](screenshots/demo-walkthrough/04-reviewed-levels-and-jd.jpg)

### 5. Xác nhận hồ sơ và xem Tóm tắt

Tab Tóm tắt báo 4/4 kỹ năng bắt buộc, 0/3 kỹ năng ưu tiên và chỉ số bao phủ JD tổng hợp 85%.

![Kết quả tóm tắt](screenshots/demo-walkthrough/05-summary.jpg)

### 6. Xem Khoảng cách

Theo kỹ năng đã có, mức đáp ứng vị trí là 50%.

![Khoảng cách theo kỹ năng hiện có](screenshots/demo-walkthrough/06-gap-presence.jpg)

Sau khi đồng ý quy tắc tính Level chưa khai báo là 0 cho lần đánh giá này, mức đáp ứng theo Level là 34,2%.

![Khoảng cách theo Level](screenshots/demo-walkthrough/07-gap-level.jpg)

### 7. Xem Lộ trình và Tài liệu

Lộ trình đưa ra 9 bước học; bước đầu là tư duy phân tích.

![Bước học đầu tiên](screenshots/demo-walkthrough/08-roadmap.jpg)

Tab Tài liệu có nguồn học cho kỹ năng cần bổ sung và nút tải báo cáo Markdown/CSV/JSON.

![Học liệu SQL](screenshots/demo-walkthrough/09-materials.jpg)

### 8. Thử Phỏng vấn

Ứng dụng tạo ba câu hỏi cho Data Analyst.

![Tab Phỏng vấn](screenshots/demo-walkthrough/10-interview.jpg)

Đã gửi câu trả lời tổng hợp cho câu đầu; chế độ rubric offline hiển thị 10,0/10 cùng các ý đã nhận diện và bằng chứng.

![Phản hồi câu trả lời demo](screenshots/demo-walkthrough/11-interview-answer.jpg)

## Điểm giao diện cần xem lại

- Thanh điều hướng cố định che một phần nội dung gần đầu khung nhìn, rõ nhất ở bước rà soát Level và các tab dài. Chữ trong logo cũng chồng lên nhãn điều hướng ở khung 903 px.
- Sau khi xác nhận, biểu mẫu Bước 1 hiện trống trở lại phía trên kết quả đã lưu. Cách trình bày này có thể khiến người xem tưởng dữ liệu demo đã mất, dù kết quả vẫn còn trong phiên.
- Trong tab Phỏng vấn, tiêu đề phản hồi là “Nhận xét AI” ngay cả khi phía dưới ghi rõ “Chấm theo từ khóa rubric — không dùng LLM”. Câu FAQ “Luyện phỏng vấn có chấm điểm câu trả lời của mình không?” hiện trả lời “Không”, trong khi luồng vừa chạy có điểm 10,0/10. Nên thống nhất hai phần này trước khi dùng để giới thiệu sản phẩm.
- Ảnh JD chỉ cho thấy phần đầu ô nhập vì ô hiển thị thấp; người dùng phải cuộn trong ô để rà lại toàn bộ yêu cầu. Có thể cân nhắc chiều cao lớn hơn hoặc bản xem trước ở bước rà soát.

## Văn bản demo để nhập lại

**CV dán**

```text
HỒ SƠ DEMO — KHÔNG PHẢI NGƯỜI THẬT
Mục tiêu: Data Analyst, phân tích dữ liệu bán lẻ và xây dựng báo cáo.
Kỹ năng: SQL, Python, Excel, Power BI, làm sạch dữ liệu, trực quan hóa dữ liệu.
Kinh nghiệm giả lập: Thực tập phân tích dữ liệu tại doanh nghiệp bán lẻ giả lập (2025). Dùng SQL tổng hợp đơn hàng, Python/pandas xử lý dữ liệu thiếu, Excel đối chiếu số liệu và Power BI tạo dashboard doanh thu.
Dự án giả lập: Phân tích doanh số theo sản phẩm và khu vực; trình bày xu hướng, ghi rõ giả định và giới hạn dữ liệu.
```

**JD đối chiếu**

```text
DATA ANALYST — MÔ TẢ CÔNG VIỆC DEMO
Yêu cầu bắt buộc:
SQL
Python
Excel
Power BI
Ưu tiên:
Tableau
Thống kê
Giao tiếp
```

Để xem lại trực tiếp: chạy `.\.venv\Scripts\python.exe -m streamlit run app.py`, mở `http://localhost:8501`, rồi nhập các giá trị trong bảng trên. Hồ sơ trong trình duyệt hiện tại đã được xác nhận; dữ liệu phiên Streamlit có thể mất khi tải lại trang hoặc dừng máy chủ.
