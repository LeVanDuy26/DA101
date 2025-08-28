## 1. Big Data là gì?

### 1.1. Khái niệm

* **Big Data** là tập hợp dữ liệu có **quy mô rất lớn, phức tạp, đa dạng**, vượt quá khả năng xử lý của các công cụ quản lý dữ liệu truyền thống (Excel, SQL cơ bản).
* Big Data thường được xử lý bằng các công nghệ đặc thù như Hadoop, Spark, NoSQL, Data Lake…

---

### 1.2. 3 tiêu chí cần đảm bảo (3V)

1. **Volume (Khối lượng dữ liệu):**

   * Lượng dữ liệu cực kỳ lớn (từ TB, PB đến EB).
   * Ví dụ: Facebook lưu trữ hàng tỷ bức ảnh và status mỗi ngày.

2. **Variety (Đa dạng dữ liệu):**

   * Dữ liệu đến từ nhiều nguồn, nhiều định dạng khác nhau (văn bản, ảnh, video, log hệ thống, giao dịch…).
   * Ví dụ: Dữ liệu khách hàng từ app ngân hàng, camera ATM, lịch sử giao dịch, social media.

3. **Velocity (Tốc độ xử lý):**

   * Dữ liệu phát sinh liên tục và cần xử lý gần như **real-time**.
   * Ví dụ: Hệ thống thanh toán trực tuyến cần xử lý hàng nghìn giao dịch/giây và phát hiện gian lận ngay lập tức.

---

### 1.3. Ví dụ

* **Là Big Data:**

  * Giao dịch chứng khoán trên toàn cầu mỗi giây.
  * Dữ liệu từ hàng triệu thiết bị IoT (cảm biến trong nhà máy, xe tự lái).
  * Lịch sử giao dịch và hành vi của hàng triệu khách hàng trong ngân hàng.

* **Không phải Big Data:**

  * File Excel lưu bảng lương của một công ty 200 nhân viên.
  * Database MySQL lưu thông tin sinh viên trong một trường đại học.

---

## 2. Ba kiểu dữ liệu

### 2.1. Dữ liệu có cấu trúc (Structured Data)

* **Định nghĩa:** Dữ liệu được tổ chức chặt chẽ, lưu trong bảng (rows – columns), dễ dàng truy vấn bằng SQL.
* **Ví dụ:**

  * Bảng giao dịch ngân hàng (ngày, số tiền, tài khoản, loại giao dịch).
  * Bảng điểm sinh viên (MSSV, tên, điểm).

---

### 2.2. Dữ liệu bán cấu trúc (Semi-Structured Data)

* **Định nghĩa:** Không lưu trong bảng cứng nhắc, nhưng vẫn có cấu trúc định dạng giúp phân tích được.
* **Thường lưu dưới dạng:** XML, JSON, logs.
* **Ví dụ:**

  * File JSON ghi lại lịch sử click của khách hàng trên website thương mại điện tử.
  * Email (có header chuẩn: người gửi, người nhận, thời gian + phần nội dung tự do).

---

### 2.3. Dữ liệu không cấu trúc (Unstructured Data)

* **Định nghĩa:** Dữ liệu không có cấu trúc rõ ràng, khó lưu trữ/truy vấn bằng SQL.
* **Ví dụ:**

  * Video khách hàng giao dịch tại ATM.
  * Bình luận trên Facebook.
  * Bản ghi âm cuộc gọi tại Call Center.

---

## 3. Tổng kết ghi nhớ

| Khái niệm                          | Đặc điểm                                                                    | Ví dụ                                               |
| ---------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------- |
| **Big Data**                       | Dữ liệu có **Volume – Variety – Velocity** vượt khả năng xử lý truyền thống | Dữ liệu giao dịch chứng khoán toàn cầu, dữ liệu IoT |
| **Structured** (có cấu trúc)       | Lưu theo hàng & cột, dễ truy vấn SQL                                        | Bảng giao dịch ngân hàng                            |
| **Semi-Structured** (bán cấu trúc) | Có định dạng nhưng không hoàn toàn theo bảng                                | JSON, XML, Email                                    |
| **Unstructured** (không cấu trúc)  | Không theo khuôn mẫu, khó xử lý trực tiếp                                   | Video, ảnh, audio, comment FB                       |

---