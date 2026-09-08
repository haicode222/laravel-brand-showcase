# Brand Product Showcase & CMS Website

Dự án xây dựng Website Quảng bá Sản phẩm Thương hiệu tích hợp Hệ thống Quản trị Nội dung (CMS), phát triển trên nền tảng **Laravel Framework** theo mô hình MVC. Dự án được triển khai và quản lý theo phương pháp luận **Agile/Scrum**.

---

## 📌 Tính năng chính

### 1. Phân hệ Khách hàng (Guest / Client-facing)
* **Trang chủ:** Trình diễn banner thương hiệu, danh sách sản phẩm nổi bật (ghim) và sản phẩm mới cập nhật.
* **Danh mục sản phẩm:** Hiển thị danh sách sản phẩm dạng lưới (Grid) có hỗ trợ phân trang (Pagination).
* **Tra cứu & Tìm kiếm:** Tìm kiếm sản phẩm theo từ khóa (tên, mô tả); lọc theo khoảng giá và danh mục.
* **Chi tiết sản phẩm:** Xem thông số kỹ thuật, mô tả chi tiết, hình ảnh chất lượng cao và giá bán.

### 2. Phân hệ Quản trị (Admin CMS)
* **Xác thực & Bảo mật:** Đăng nhập, đăng xuất, mã hóa mật khẩu Bcrypt, bảo vệ phiên làm việc (Session) và chống CSRF.
* **Quản lý Danh mục (Category CRUD):** Thêm, xem bảng danh mục, chỉnh sửa và xóa danh mục sản phẩm.
* **Quản lý Sản phẩm (Product CRUD):** Thêm mới (kèm upload hình ảnh vào Storage), xem danh sách phân trang, sửa thông tin và xóa sản phẩm.
* **Cấu hình Trưng bày:** Ghim / Bỏ ghim sản phẩm tiêu biểu trực tiếp ra khu vực nổi bật của Trang chủ.

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

* **Backend:** PHP >= 8.1, Laravel Framework (Eloquent ORM, Blade Engine, RESTful Routing).
* **Database:** MySQL.
* **Frontend:** Blade Template, HTML5, CSS3, JavaScript.
* **Quản lý mã nguồn & Dự án:** Git, GitHub, Jira Software (Agile/Scrum), PlantUML.

---

## ⚙️ Yêu cầu hệ thống

* PHP >= 8.1
* Composer >= 2.x
* MySQL >= 5.7 hoặc MariaDB >= 10.3
* Web Server (Apache / Nginx qua XAMPP, Laragon hoặc Docker)

---
