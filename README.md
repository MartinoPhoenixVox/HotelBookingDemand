# 🏨 Phân Tích Nhu Cầu Đặt Chỗ Khách Sạn

![Hotel Booking Demand Analysis](https://img.freepik.com/free-vector/hotel-building-city-urban-architecture-skyline_107791-10115.jpg?w=1380&t=st=1708892400~exp=1708893000~hmac=6b9b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b8b)
_Phân tích hành vi và xu hướng đặt phòng để tối ưu hóa chiến lược kinh doanh khách sạn._

## ✨ Giới Thiệu

Dự án này là một phân tích chuyên sâu về **nhu cầu đặt chỗ khách sạn**, sử dụng bộ dữ liệu thực tế về thông tin đặt phòng. Mục tiêu chính là khám phá các **xu hướng nổi bật**, nhận diện **đặc điểm khách hàng** và cung cấp những **thông tin chi tiết giá trị** về hành vi đặt phòng, giúp đưa ra các quyết định kinh doanh hiệu quả.

## 🚀 Các Tính Năng & Phân Tích Chính

* **Dọn dẹp & Tiền xử lý Dữ liệu:** Đảm bảo dữ liệu sạch, không có giá trị thiếu và được định dạng chuẩn xác để sẵn sàng cho phân tích.
* **Phân Tích Khám phá Dữ liệu (EDA):**
    * Cái nhìn tổng quan về cấu trúc và phân phối của dữ liệu.
    * Phân tích mối tương quan giữa các biến để phát hiện các mối quan hệ tiềm ẩn.
* **Gom Cụm K-Means:**
    * Áp dụng thuật toán K-Means để phân tích mối liên hệ giữa **tuần trong năm** và **giá phòng cho thuê** cho hai bộ dữ liệu "H1" (City Hotel) và "H2" (Resort Hotel).
    * Sử dụng phương pháp **Elbow Method** để xác định số lượng cụm tối ưu, đảm bảo kết quả phân tích chính xác nhất.
    * **Insights:** Đưa ra nhận định sâu sắc về hành vi đặt chỗ của khách hàng (ví dụ: khách hàng giá rẻ, khách hàng cao cấp) dựa trên các cụm được hình thành và thời điểm trong năm.

## 📊 Nguồn Dữ Liệu

Bộ dữ liệu được sử dụng trong dự án này cung cấp thông tin đặt chỗ chi tiết, cho phép phân tích toàn diện về hành vi người dùng.

* **Nguồn:** [https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005](https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005)

## 💻 Công Nghệ & Thư Viện

Dự án được xây dựng trên nền tảng Python với sự hỗ trợ của các thư viện mạnh mẽ:

* **Ngôn ngữ:** Python
* **Thư viện:**
    * `pandas`: Xử lý, thao tác và phân tích dữ liệu hiệu quả.
    * `numpy`: Hỗ trợ các phép toán số học phức tạp.
    * `matplotlib`, `seaborn`: Tạo ra các biểu đồ và đồ thị trực quan hóa dữ liệu đẹp mắt, dễ hiểu.
    * `scikit-learn`: Triển khai các thuật toán học máy, đặc biệt là K-Means cho phân tích cụm.

## 🚀 Hướng Dẫn Sử Dụng

Để khám phá và tái tạo các phân tích trong dự án:

1.  **Sao chép Repository:**
    ```bash
    git clone <URL_REPOSITORY_CỦA_BẠN>
    cd <TÊN_THƯ_MỤC_DỰ_ÁN>
    ```
    (Thay `<URL_REPOSITORY_CỦA_BẠN>` bằng URL thực tế của GitHub repo của bạn).
2.  **Cài đặt Môi trường:**
    Đảm bảo bạn đã cài đặt các thư viện Python cần thiết:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Chạy Phân Tích:**
    Mở file `HotelBookingDemand.ipynb` bằng Jupyter Notebook hoặc Google Colab và chạy từng ô để xem và hiểu các bước phân tích dữ liệu.

## 👤 Thành Viên Dự Án

* **Võ Huỳnh Thanh Phương** - Mã sinh viên: 2151013072

## 📧 Liên Hệ

Mọi câu hỏi, góp ý hoặc mong muốn hợp tác đều được hoan nghênh!

* **Email:** [phuong.vht.0504@gmail.com](mailto:phuong.vht.0504@gmail.com)

---

**Thông tin khóa học:**

* **Môn học:** Phân tích dữ liệu
* **Giảng viên:** ThS. Hồ Hướng Thiên
* **Lớp:** CS2101

---
