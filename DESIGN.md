# DESIGN.md — Gác Đọc: Landing page tiệm sách độc lập

Tài liệu thiết kế cho landing page 1 trang của tiệm sách độc lập Gác Đọc.
Task: TEC-234. Epic: TEC-233. Repo: https://github.com/Muse-Soft/m-software-gac-doc

> Mọi giá trên trang là giá mẫu. Mọi thông tin thật chưa có (địa chỉ, giờ mở cửa,
> số điện thoại, email, tên người liên hệ) đều để placeholder `[CẦN BỔ SUNG]` —
> không bịa số liệu thật.

## 1. Bảng màu (mã hex + vai trò từng màu)

| Mã hex | Tên gọi | Vai trò |
|---|---|---|
| `#F6F0E4` | Giấy kem | Màu nền chính toàn trang — nền giấy cũ, ấm, dịu mắt khi đọc lâu |
| `#2E2620` | Nâu mực | Màu chữ chính: tiêu đề, đoạn văn, nhãn — độ tương phản cao trên nền giấy kem |
| `#8C3B2E` | Đỏ gạch | Màu nhấn duy nhất: nút kêu gọi hành động (đặt giữ sách, đăng ký thành viên), tiêu đề section, giá sách nổi bật, gạch chân link |
| `#E8DCC8` | Giấy sẫm | Màu nền phụ: khối trích dẫn, thẻ sách, nền section xen kẽ với nền chính |
| `#6B5B4A` | Nâu gỗ nhạt | Màu chữ phụ: chú thích ảnh, mô tả nhỏ, chân trang |
| `#FFFFFF` | Trắng giấy | Chỉ dùng trong khung ảnh bìa sách và thẻ form, để bìa sách nổi trên nền kem |

Quy tắc dùng màu: nền luôn là `#F6F0E4` hoặc `#E8DCC8` xen kẽ theo section;
không dùng thêm màu lạnh (xanh dương, xám xanh) hay màu neon. Nút chính:
nền `#8C3B2E`, chữ `#F6F0E4`. Nút phụ: viền `#8C3B2E`, chữ `#8C3B2E`,
nền trong suốt.

## 2. Font chữ

- **Font tiêu đề: Playfair Display** (Google Fonts, serif có chân, nét thanh đậm
  tương phản cao). Dùng cho: tên tiệm "Gác Đọc", tiêu đề hero, tiêu đề mỗi
  section, tên sách nổi bật. Cỡ: hero 56–72px (desktop) / 36–44px (mobile);
  tiêu đề section 32–40px; tên sách 20–24px. Độ đậm: 700 cho hero,
  600 cho tiêu đề section.
- **Font nội dung: Be Vietnam Pro** (Google Fonts, sans-serif, hỗ trợ đầy đủ
  tiếng Việt có dấu). Dùng cho: đoạn mô tả, giá sách, lịch sinh hoạt, nhãn form,
  nút bấm, chân trang. Cỡ: thân bài 16–18px, chú thích 14px, nhãn form 15px.
  Độ đậm: 400 cho thân bài, 600 cho nhãn và nút.
- Quy tắc: không dùng font thứ ba. Tiêu đề không viết hoa toàn bộ; chỉ viết hoa
  chữ cái đầu câu và tên riêng.

## 3. Phong cách tham chiếu (một phong cách duy nhất)

**Tiệm sách Shakespeare and Company ở Paris — ấm cúng, cổ điển, đầy sách.**

Áp dụng cụ thể: kệ sách gỗ cao chạm trần, xếp sách sát nhau nhiều lớp, có
thang trượt dọc kệ; ghế bành và ghế gỗ cũ đặt xen giữa các kệ; ánh đèn vàng
ấm (2700–3000K) thay vì đèn trắng; giấy cũ, bìa vải, tem giấy và biển hiệu
viết tay làm điểm trang trí; không gian chật vừa phải, nhiều sách, ít khoảng
trống lạnh. Trang web phải gợi cảm giác "bước vào một căn gác đầy sách"
ngay từ hero, không gợi cảm giác cửa hàng hiện đại, tối giản, nhiều kính
và kim loại.

## 4. Quy tắc hình ảnh

- **Ảnh là nội dung chính, không phải trang trí:** hero là ảnh lớn toàn màn hình
  (full viewport, tỉ lệ 16:9 trên desktop, ảnh dọc 4:5 phủ màn hình trên mobile)
  chụp kệ sách gỗ cao chạm trần dưới ánh đèn vàng ấm; mỗi kệ sách tuyển chọn
  dùng ảnh bìa sách lớn, tối thiểu 3 bìa mỗi chủ đề.
- **Tông ảnh: đồng tông ấm.** Tất cả ảnh phải qua tông ấm: ánh sáng vàng,
  gỗ nâu, giấy kem — không ảnh tông lạnh, không ảnh HDR gắt, không ảnh
  studio nền trắng tách vật thể (trừ ảnh bìa sách đơn lẻ trong lưới kệ).
- **Chất liệu chủ đạo trong ảnh: gỗ và giấy cũ.** Ưu tiên ảnh có kệ gỗ, bàn gỗ,
  giấy ố vàng, bìa vải, gáy sách sờn. Tránh ảnh có nhiều kim loại sáng,
  kính phản chiếu, nhựa bóng.
- **Tỉ lệ khung ảnh:**
  - Hero: 16:9 (desktop) / 4:5 (mobile), phủ toàn màn hình.
  - Ảnh không gian đọc / góc cà phê sách: 4:3, chụp ghế bành, cửa sổ,
    ánh sáng tự nhiên ban ngày.
  - Ảnh bìa sách trong lưới kệ: 3:4 (tỉ lệ bìa sách thật), nền `#FFFFFF`
    trong thẻ, viền bóng đổ nhẹ.
  - Ảnh sự kiện (câu lạc bộ đọc, ký tặng): 16:9 hoặc 4:3, chụp người đọc
    sách và tác giả trong không gian tiệm, không chụp sân khấu lớn.
- **Bố cục: ảnh lớn + khoảng trắng.** Mỗi section chỉ có tối đa 1 ảnh lớn
  hoặc 1 lưới ảnh; giữa các section chừa khoảng trắng (padding dọc 80–120px
  desktop, 48–64px mobile) nền `#F6F0E4`, không xếp ảnh sát nhau thành lưới
  dày đặc. Chữ không đè lên vùng chi tiết chính của ảnh; chữ trên hero đặt
  trên lớp phủ tối mờ 40% ở nửa dưới ảnh.

## 5. Cấu trúc trang (1 trang, từ trên xuống)

1. **Hero:** ảnh lớn toàn màn hình kệ sách gỗ cao chạm trần, đèn vàng ấm;
   tên "Gác Đọc" (Playfair Display), dòng giới thiệu 1 câu, nút đỏ gạch
   "Đặt giữ sách" và "Đăng ký thành viên" (cuộn xuống form cuối trang).
2. **Kệ sách tuyển chọn:** 3 chủ đề — Văn học, Thiếu nhi, Sách nghệ thuật.
   Mỗi chủ đề: tiêu đề + tối thiểu 3 bìa sách ảnh lớn (3:4) kèm tên sách
   và giá mẫu (ghi rõ "giá mẫu").
3. **Không gian đọc & góc cà phê sách:** ảnh 4:3 ghế bành, cửa sổ, ánh sáng
   tự nhiên; mô tả ngắn về chỗ ngồi đọc tại chỗ và đồ uống (giá mẫu,
   menu thật: `[CẦN BỔ SUNG]`).
4. **Lịch sinh hoạt:** câu lạc bộ đọc định kỳ + buổi ký tặng cuối tuần;
   mỗi mục ghi ngày/giờ mẫu, địa điểm trong tiệm, ghi chú "lịch mẫu —
   lịch thật: `[CẦN BỔ SUNG]`".
5. **Form cuối trang (chỉ giao diện, chưa xử lý thật):** form đặt giữ sách
   (tên sách, họ tên, số điện thoại) và form đăng ký thành viên (họ tên,
   email); nút gửi màu đỏ gạch; ghi chú dưới form: "Form chỉ giao diện —
   dữ liệu chưa được gửi đi thật."
6. **Chân trang:** tên tiệm, địa chỉ / giờ mở cửa / liên hệ — tất cả là
   `[CẦN BỔ SUNG]` nếu chưa có thông tin thật.

## 6. Ghi chú cho Dev (mức ưu tiên khi dựng trang)

- Ưu tiên bố cục ảnh lớn + khoảng trắng theo mục 4 và 5; không thu nhỏ ảnh
  hero để nhét thêm chữ.
- Ảnh mẫu dùng ngay từ bản đầu tiên phải đồng tông ấm, nhiều gỗ và giấy cũ;
  ghi rõ là ảnh mẫu trong comment kết quả của task Dev.
- Responsive: mobile 1 cột, ảnh hero 4:5; desktop tối đa 1200px chiều rộng
  nội dung, căn giữa.
