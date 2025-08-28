## 📌 Hành trình của dữ liệu trong công ty

### 1. **Thu thập dữ liệu (Data Collection)**

* **Nguồn dữ liệu:**

  * Hệ thống giao dịch (POS, ATM, app ngân hàng).
  * Website, ứng dụng di động.
  * Thiết bị IoT, cảm biến.
  * Mạng xã hội, khảo sát khách hàng.
* **Ví dụ:**

  * Ngân hàng thu thập dữ liệu giao dịch thẻ, lịch sử tín dụng.
  * Siêu thị thu thập dữ liệu hóa đơn, hành vi mua hàng.

---

### 2. **Lưu trữ dữ liệu (Data Storage)**

* **Cách lưu trữ:**

  * Database quan hệ (MySQL, Oracle) cho dữ liệu có cấu trúc.
  * Data Lake (Hadoop, AWS S3) cho dữ liệu lớn và đa dạng.
  * Data Warehouse (Snowflake, BigQuery, Redshift) cho phân tích.
* **Ví dụ:**

  * Ngân hàng dùng **Data Warehouse** để tổng hợp dữ liệu khách hàng từ nhiều chi nhánh.
  * Công ty bán lẻ lưu trữ dữ liệu bán hàng trong **cloud storage**.

---

### 3. **Xử lý & Làm sạch dữ liệu (Data Processing & Cleaning)**

* **Hoạt động:**

  * Loại bỏ dữ liệu trùng lặp, xử lý giá trị thiếu.
  * Chuẩn hóa định dạng (ngày tháng, tiền tệ).
  * Kết hợp nhiều nguồn dữ liệu.
* **Ví dụ:**

  * Hợp nhất hồ sơ khách hàng từ nhiều hệ thống để có **một bản ghi duy nhất (Single Customer View)**.
  * Chuẩn hóa dữ liệu “20,000 VND” và “20000” về cùng định dạng số.

---

### 4. **Phân tích dữ liệu (Data Analysis)**

* **Mức độ phân tích:**

  * Descriptive → “Chuyện gì đã xảy ra?”
  * Diagnostic → “Tại sao?”
  * Predictive → “Điều gì sẽ xảy ra?”
  * Prescriptive → “Nên làm gì?”
* **Ví dụ:**

  * Ngân hàng phân tích nguyên nhân nợ xấu tăng.
  * Công ty bán lẻ dự báo nhu cầu bia rượu dịp Tết.

---

### 5. **Trực quan hóa & Báo cáo (Data Visualization & Reporting)**

* **Công cụ:** Power BI, Tableau, Google Data Studio.
* **Mục tiêu:** Giúp lãnh đạo, quản lý dễ dàng hiểu dữ liệu qua dashboard, biểu đồ.
* **Ví dụ:**

  * Dashboard KPI doanh số theo chi nhánh.
  * Biểu đồ nợ xấu theo ngành nghề khách hàng vay.

---

### 6. **Ra quyết định kinh doanh (Decision Making)**

* **Mục tiêu:** Biến dữ liệu thành hành động cụ thể.
* **Ví dụ:**

  * Ngân hàng quyết định siết chặt tín dụng bất động sản dựa trên dữ liệu nợ xấu.
  * Siêu thị giảm giá & tăng khuyến mãi khi thấy tồn kho cao.

---

### 7. **Tự động hóa (Automation)** *(mức cao nhất)*

* **Mục tiêu:** Hệ thống tự động đưa ra quyết định dựa trên dữ liệu theo thời gian thực.
* **Ví dụ:**

  * Hệ thống ngân hàng tự động **chặn giao dịch gian lận** trong vài giây.
  * Amazon tự động gợi ý sản phẩm phù hợp cho khách hàng.

---

## 🎯 Tổng kết ghi nhớ

| Bước                 | Nội dung                                | Ví dụ                           |
| -------------------- | --------------------------------------- | ------------------------------- |
| **1. Thu thập**      | Lấy dữ liệu từ nhiều nguồn              | Giao dịch ATM, hóa đơn siêu thị |
| **2. Lưu trữ**       | Lưu trong DB, Data Lake/Warehouse       | Ngân hàng lưu Data Warehouse    |
| **3. Làm sạch**      | Xử lý thiếu, trùng, chuẩn hóa           | Chuẩn hóa dữ liệu tiền tệ       |
| **4. Phân tích**     | Descriptive → Predictive → Prescriptive | Dự báo nhu cầu hàng Tết         |
| **5. Trực quan hóa** | Dashboard, báo cáo                      | KPI doanh số theo khu vực       |
| **6. Quyết định**    | Dựa trên insight để hành động           | Giảm giá hàng tồn kho           |
| **7. Tự động hóa**   | Hệ thống ra quyết định real-time        | Chặn gian lận thẻ tín dụng      |