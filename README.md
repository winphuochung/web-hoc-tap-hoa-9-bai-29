# Web/app học tập — Hóa học 9, Bài 29

**Bài 29: Carbohydrate (glucose và saccharose)**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động (ô chữ bí mật ôn Bài 28), Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Thí nghiệm phản ứng tráng bạc của glucose (SGK tr. 132–133, 4 bước đúng quy trình) kèm ống đối chứng saccharose — hình SVG thay đổi theo từng bước: ống glucose xuất hiện lớp bạc trắng xám bám thành ống sau khi ngâm nước nóng 70–80 °C, ống saccharose không có hiện tượng gì.

Phản ứng lên men rượu của glucose và phản ứng thuỷ phân của saccharose chỉ trình bày lý thuyết trong SGK (không có thí nghiệm kèm theo) nên chỉ có ở mục Khám phá, không dựng thành mô phỏng.

Khóa đáp án trắc nghiệm: 1A 2C 3D 4B 5A 6B 7D 8C 9A 10D.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm hiện chỉ lưu trên máy học sinh (localStorage).

## Trạng thái gửi điểm về Google Sheets

**CHỜ /exec** — Google đang chặn tạo dự án Apps Script mới nên bài này chưa có Web App URL. File `index.html` hiện KHÔNG chứa fetch gửi điểm (0 lần xuất hiện chuỗi `script.google.com`). Khi deploy xong, parent sẽ patch URL Web App vào file; file `Code.gs` trong thư mục này đã sẵn sàng để deploy.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai29.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script ghi điểm vào Google Sheets (tab KetQua), chờ deploy.
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo cá nhân thầy Lê Văn Thắng (`logo-le-van-thang.png`, 500×500, nền trong suốt).
