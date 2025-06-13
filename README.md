```markdown
# 🏨 Phân Tích Nhu Cầu Đặt Chỗ Khách Sạn

## 🚀 Giới Thiệu

Dự án này tập trung vào việc **phân tích nhu cầu đặt chỗ khách sạn** dựa trên bộ dữ liệu về thông tin đặt phòng. Mục tiêu là khám phá các xu hướng, đặc điểm của khách hàng, và đưa ra những nhận định hữu ích về hành vi đặt phòng.

## ✨ Tính Năng Chính

* **Tiền xử lý dữ liệu:** Làm sạch, xử lý thiếu giá trị và định dạng dữ liệu.
* **Khám phá dữ liệu (EDA):** Phân tích tổng quan, mối tương quan giữa các biến.
* **Gom cụm K-Means:**
    * Phân tích mối liên hệ giữa tuần trong năm và giá cho thuê phòng cho hai bộ dữ liệu "H1" và "H2".
    * Sử dụng phương pháp Elbow để xác định số cụm tối ưu.
    * Nhận định về hành vi đặt chỗ của khách hàng (khách hàng giá rẻ, khách hàng cao cấp) theo thời gian.

## 📊 Bộ Dữ Liệu

Dự án sử dụng bộ dữ liệu về nhu cầu đặt chỗ khách sạn, cung cấp thông tin chi tiết về các giao dịch đặt phòng.

* Nguồn: [https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005](https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005)

## 🛠️ Công Nghệ & Thư Viện

* **Ngôn ngữ:** Python
* **Thư viện:**
    * `pandas`: Xử lý và phân tích dữ liệu.
    * `numpy`: Tính toán số học.
    * `matplotlib`, `seaborn`: Trực quan hóa dữ liệu.
    * `scikit-learn`: Thuật toán K-Means.

## 📁 Cấu Trúc Dự Án

```
.
├── Datasets                      # Thư mục chứa datasets liên quan
├── HotelBookingDemand.ipynb      # Notebook Jupyter chứa mã nguồn phân tích
```

## 📝 Cách Chạy Dự Án

1.  Clone repository về máy của bạn:
    ```bash
    git clone <URL_REPOSITORY_CỦA_BẠN>
    ```
2.  Cài đặt các thư viện cần thiết (nếu chưa có):
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Mở và chạy file `HotelBookingDemand.ipynb` bằng Jupyter Notebook hoặc Google Colab để xem toàn bộ quá trình phân tích.

## 👥 Thành Viên Thực Hiện

* Võ Huỳnh Thanh Phương - 2151013072

## 📧 Liên Hệ

Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, vui lòng liên hệ:
[phuong.vht.0504@gmail.com](mailto:phuong.vht.0504@gmail.com)

---

**Môn học:** Phân tích dữ liệu
**Giảng viên:** ThS. Hồ Hướng Thiên
**Lớp:** CS2101

```
