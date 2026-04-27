# Partybox 120 DIY Project

Dự án thiết kế và chế tạo loa di động DIY dựa trên cấu hình âm thanh của dòng JBL Partybox 120, kết hợp giữa kỹ thuật in 3D và thiết kế cơ khí chính xác.

## 📌 Thông số kỹ thuật (Specifications)
* **Bass:** Sử dụng củ loa Bass JBL Partybox 120 (hoặc tương đương).
* **Mid-range:** Hỗ trợ driver dải trung từ 2.5 - 3 inch.
* **Chất liệu vỏ:** Thiết kế tối ưu cho in 3D (nhựa PETG/ABS hoặc gỗ PDF hoặc gỗ thịt được khuyến khích để chịu lực và nhiệt tốt).
* **Phần mềm thiết kế:** SolidWorks 2024.

## 📂 Cấu trúc thư mục (File Structure)
* `/box_mid_ver2.SLDPRT`: File thiết kế gốc SolidWorks cho khoang loa mid (Version 2).
* `/quai.SLDPRT`: File thiết kế quai xách của loa.
* `/*.3mf`: Các file đã qua xử lý lưới (mesh) sẵn sàng để đưa vào phần mềm cắt lớp (Bambu Studio, Cura) để in 3D.

## 🛠 Hướng dẫn chế tạo
1. **In 3D:** Sử dụng các file `.3mf` tương ứng. Ưu tiên độ dày thành (wall line count) từ 4 lớp trở lên để đảm bảo độ kín âm (Acoustic enclosure).
2. **Lắp ráp:** Sử dụng các file `.SLDPRT` để tham chiếu vị trí lắp ghép các khớp nối và vít.
3. **Xử lý âm học:** Nên lót bông tiêu âm vào khoang mid để giảm nhiễu phản xạ.

## ⚖️ Bản quyền (License)
Dự án này được lưu trữ  cho mục đích  thoả mãn đam mê và chế tạo thủ công (DIY).
