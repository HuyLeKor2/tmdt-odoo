# 📦 Tối Ưu Hóa Quy Trình Bán Hàng Thương Mại Điện Tử với Odoo
LINK: https://drive.google.com/drive/folders/18m-c7PsXEZGkvOsT0mvCJ4V9WIG7mFpZ

Đây là đồ án tốt nghiệp của nhóm sinh viên ngành Công nghệ Thông tin tại **Trường Đại học Sài Gòn**, với mục tiêu xây dựng một hệ thống **tối ưu hóa quy trình bán hàng** cho doanh nghiệp thương mại điện tử sử dụng nền tảng **Odoo (ERP mã nguồn mở)**.  

Dự án hướng đến mô phỏng quy trình thực tế: từ quản lý sản phẩm, đơn hàng, khách hàng đến khuyến mãi, nhằm phục vụ bài toán triển khai ERP trong môi trường doanh nghiệp vừa và nhỏ.

---

## 👨‍💻 Thành viên thực hiện

- **Lê Nguyễn Minh Huy** – Xây dựng giao diện người dùng & xử lý các chức năng frontend  
- **Võ Khương Duy** – Tích hợp hệ thống, kiểm thử  
- **Trần Kim Phú** – Logic nghiệp vụ, quản trị sản phẩm  
- **Trần Trọng Phú** – Tích hợp thanh toán và báo cáo  
- **Phạm Bảo Nghiêm** – Thiết kế UX/UI, tài liệu báo cáo  
- **GVHD**: Trần Đình Nghĩa
---

## 🚀 Các chức năng nổi bật

- ✅ Quản lý tài khoản người dùng: đăng ký, đăng nhập, cập nhật hồ sơ  
- ✅ Danh mục sản phẩm & phân loại: tìm kiếm, lọc sản phẩm  
- ✅ Giỏ hàng & đơn hàng: thêm/xoá sản phẩm, thanh toán, theo dõi đơn hàng  
- ✅ Tích hợp thanh toán: chuyển khoản ngân hàng & mô phỏng cổng thanh toán  
- ✅ Chức năng khuyến mãi: mã giảm giá, thẻ tích điểm, chương trình “mua X tặng Y”  
- ✅ Giao diện quản trị: thống kê doanh số, quản lý sản phẩm & đơn hàng

---

## 🛠️ Công nghệ sử dụng

- **Odoo 17 (Community Edition)**  
- **Python 3.10+**  
- **PostgreSQL 14**  
- **Triển khai cục bộ & sẵn sàng triển khai trên AWS/DigitalOcean**

---

## 📷 Hình ảnh minh họa

- Trang sản phẩm, chi tiết sản phẩm  
- Trang giỏ hàng và thanh toán  
- Giao diện quản trị viên  
- Module khuyến mãi, quản lý đơn hàng  
> Tất cả ảnh chụp màn hình có thể xem trong thư mục `/docs/screenshots` hoặc tài liệu báo cáo.

---

## 📘 Cách cài đặt và chạy thử

```bash
# Clone repo
git clone https://github.com/ten-ban/odoo-ecommerce-sales.git
cd odoo-ecommerce-sales

# Cài đặt thư viện phụ thuộc
pip install -r requirements.txt

# Chạy Odoo server
./odoo-bin -c odoo.conf
