<p align="center">
  <a href="https://hcmus.edu.vn//" title="Trường Đại học Khoa Học Tự Nhiên " style="border: none;">
    <img src="https://fetel.hcmus.edu.vn/wp-content/uploads/2022/09/logo-fetel.png" alt="rường Đại học Khoa Học Tự Nhiên | University of Science">
  </a>
</p>

# Lập trình Python mô phỏng PCA .

## Giới thiệu

* Đây là bài tập được sử dụng làm đồ án cuối kì cho môn xử lý tín hiệu số.
* Bài tập được xây dựng bằng các kiến thức của DSP và ngôn ngữ Python.
* Thực hiện chương trình Phân tích thành phần chính trong Xử lý ảnh (PCA).

### Giảng viên hướng dẫn

* TS. Trần Thị Thảo Nguyên - Khoa Điện Tử - Viễn Thông , Trường Đại Học Khoa Học Tự Nhiên - ĐHQGHCM

### Sinh viên thực hiện

|**STT**|**MSSV**|  **Họ và tên**  |       **Email**      |
|-------|--------|-----------------|----------------------|
|   1   |21207077|Tran Thien Phuc  |21207077@hcmus.edu.vn |

## Chạy thử project: Phân tích thành phần chính trong Xử lý ảnh (PCA)

### Yêu cầu Thực hiện bằng Python trên Google Colab

### Bước 1: Tiền xử lý dữ liệu
* Chuẩn bị dữ liệu ảnh:
  - Tải tập dữ liệu ảnh.
  - Chuyển đổi ảnh thành ma trận dữ liệu.
  - Chuẩn hóa dữ liệu (ví dụ: chuẩn hóa Z-score).
* Thiết lập tham số PCA:
  - Xác định số lượng thành phần chính cần thiết.
  - Khởi tạo mô hình PCA.

### Bước 2: Thực hiện PCA
* Áp dụng PCA cho dữ liệu ảnh:
  - Sử dụng mô hình PCA để biến đổi dữ liệu ảnh sang không gian mới.
* Phân tích kết quả:
  - Visualize the transformed data.
* Đánh giá hiệu quả của PCA trong việc giảm nhiễu, nén ảnh, hoặc trích xuất đặc trưng.

### Bước 3: Lưu trữ và trình bày kết quả
* Lưu trữ kết quả:
  - Lưu trữ dữ liệu ảnh đã biến đổi, mô hình PCA đã được huấn luyện.
* Trình bày kết quả:
  - Hiển thị hình ảnh gốc và ảnh đã biến đổi.
  - Phân tích độ méo mó của ảnh sau khi biến đổi.
  - Đánh giá hiệu suất của PCA bằng các chỉ số định lượng phù hợp.
#### Lưu ý
- Lựa chọn thư viện Python phù hợp cho xử lý ảnh và PCA (ví dụ: NumPy, OpenCV, scikit-learn).
- Sử dụng các kỹ thuật trực quan hóa dữ liệu để đánh giá hiệu quả của PCA.
- Điều chỉnh tham số PCA để tối ưu hóa hiệu suất cho bài toán cụ thể.
- Demo project trên Google Colab
- Tạo notebook Python mới trên Google Colab.
- Thực hiện các bước tiền xử lý dữ liệu, PCA và lưu trữ kết quả như mô tả trên.
- Thêm các đoạn code cần thiết để hiển thị hình ảnh gốc và ảnh đã biến đổi, đồng thời so sánh độ méo mó giữa hai ảnh.
- Chạy notebook và lưu ý các thông tin quan trọng trong quá trình thực thi.
