# AnguLite

**Bộ công cụ desktop cho dân làm online.** 13 tool miễn phí, chạy offline, không cần đăng ký.
Windows & macOS.

*A free desktop toolbox for digital workers — 13 tools, fully offline, no account required.*

---

## ⬇️ Tải về / Download — v0.3.4

| Hệ điều hành | File | Dung lượng |
|---|---|---|
| **Windows 10/11** (64-bit) | [`AnguLite_0.3.4_x64-setup.exe`](https://github.com/anguless-com/angulite-releases/releases/latest/download/AnguLite_0.3.4_x64-setup.exe) | 9.4 MB |
| **macOS** (Apple Silicon — M1/M2/M3/M4) | [`AnguLite_0.3.4_aarch64.dmg`](https://github.com/anguless-com/angulite-releases/releases/latest/download/AnguLite_0.3.4_aarch64.dmg) | 11.9 MB |
| **macOS** (Intel) | [`AnguLite_0.3.4_x64.dmg`](https://github.com/anguless-com/angulite-releases/releases/latest/download/AnguLite_0.3.4_x64.dmg) | 12.5 MB |

> Không chắc máy Mac nào? → Apple menu →  About This Mac. Thấy "Apple M1/M2/M3/M4" thì tải bản
> Apple Silicon, thấy "Intel" thì tải bản Intel.

### 🔒 Kiểm tra file (khuyến khích) / Verify your download

**SHA256** — so sánh với file bạn vừa tải để chắc chắn không bị sửa đổi:

```
ee4674fc1d90b64062df02d1a6399a3561fc569f307529a39b1b954c697e5f2b  AnguLite_0.3.4_x64-setup.exe
f8a06190f47bd0a197fafa315dba7328447739187d044908cbeab4217d08836c  AnguLite_0.3.4_aarch64.dmg
3748d6b372c2ff57d1af6d2f20b15e8901d50cd5d6cc0cb3b2102ab4be0d3a16  AnguLite_0.3.4_x64.dmg
```

<details>
<summary>Cách kiểm tra / How to check</summary>

**Windows (PowerShell):**
```powershell
Get-FileHash .\AnguLite_0.3.4_x64-setup.exe -Algorithm SHA256
```

**macOS (Terminal):**
```bash
shasum -a 256 AnguLite_0.3.4_aarch64.dmg
```

Chuỗi in ra phải trùng khớp với ở trên. Nếu khác → xoá file và tải lại từ đúng trang này.
</details>

---

## 📦 Cài đặt / Installation

### Windows — về cảnh báo SmartScreen

Khi mở file cài đặt, Windows sẽ hiện bảng xanh **"Windows protected your PC — Unknown Publisher"**.

**Đây là bình thường và không có nghĩa là file có virus.** Windows cảnh báo với *mọi* ứng dụng
chưa được ký số (code signing certificate). Chứng chỉ đó tốn khoảng $100–400/năm và AnguLite
chưa mua — khi app có người dùng thật, đây là khoản đầu tư đầu tiên.

Để cài: bấm **More info** → **Run anyway**.

Không yên tâm? Kiểm tra SHA256 ở trên trước khi cài.

### macOS — về cảnh báo Gatekeeper

Mở file `.dmg`, kéo **AnguLite** vào thư mục **Applications**, rồi mở từ Launchpad.

Nếu macOS báo app *"cannot be opened"* hoặc *"is damaged"*:

1. Mở **System Settings** → **Privacy & Security**
2. Kéo xuống cuối, tìm dòng nhắc về AnguLite → bấm **Open Anyway**
3. Xác nhận lần nữa khi được hỏi

> Trên macOS 15 (Sequoia) trở lên, mẹo chuột-phải → Open cũ **không còn tác dụng** —
> phải vào System Settings như trên.

---

## 🧰 Có gì bên trong / What's inside

### Miễn phí — 13 tool, vĩnh viễn, không cần tài khoản

| Tool | Làm gì |
|---|---|
| **Browser Profiles** | Quét & mở nhanh mọi profile Chrome / Edge / Brave đang có trên máy |
| **System Cleaner** | Dọn temp, cache, log — kể cả cache dev (npm, cargo, pip) |
| **Batch Rename** | Đổi tên file hàng loạt: find & replace, đánh số, đổi đuôi |
| **Clipboard History** | Lịch sử copy, tìm kiếm, ghim mục hay dùng |
| **Port Manager** | Xem port nào đang bị chiếm, kill process, phát hiện xung đột |
| **PDF Tools** | Gộp, tách, nén, PDF → ảnh, ảnh → PDF |
| **Image Tools** | Resize, đổi định dạng, nén, **xoá metadata GPS**, ảnh → Base64 |
| **QR Code** | Tạo QR từ text/URL, QR WiFi, QR danh thiếp, đọc QR từ ảnh |
| **Text Tools** | Đếm từ, đổi hoa/thường, so sánh 2 văn bản, lọc trùng, sắp xếp |
| **Password Generator** | Mật khẩu ngẫu nhiên & passphrase dễ nhớ |
| **Color Picker** | Lấy màu bất kỳ trên màn hình, đổi HEX / RGB / HSL |
| **Quick Notes** | Ghi chú Markdown, tự động lưu |
| **App Uninstaller** *(chỉ macOS)* | Gỡ app sạch sẽ, dò file sót 10 tầng, chừa 27 app hệ thống |

### Pro — $5 mua đứt, không subscription

Mở khoá **vĩnh viễn**, trả một lần. Không mua thì 13 tool trên vẫn dùng bình thường, không giới hạn.

| Tool | Làm gì |
|---|---|
| **System Cleaner Pro** | Dọn rác tự động theo lịch (ngày/tuần/tháng), cảnh báo khi rác vượt ngưỡng, chạy nền ở khay hệ thống |
| **Windows Optimizer** *(chỉ Windows)* | Tinh chỉnh Windows theo nhóm, **có rollback đầy đủ** cho mọi thay đổi |

---

## 🔐 Quyền riêng tư / Privacy

- **13 tool miễn phí chạy 100% offline.** File của bạn không rời khỏi máy — không upload đi đâu cả.
- **Không cần đăng nhập** để dùng tool miễn phí. Tài khoản chỉ cần khi mua tool Pro.
- **Không quảng cáo, không bán dữ liệu, không theo dõi hành vi.**
- App chỉ kết nối mạng khi: (1) kiểm tra bản cập nhật, (2) bạn chủ động mua tool Pro.

---

## ❓ Câu hỏi thường gặp / FAQ

<details>
<summary><b>App có virus không? Sao Windows lại cảnh báo?</b></summary>

Không. Cảnh báo đó xuất hiện vì app **chưa được ký số**, không phải vì phát hiện mã độc —
Windows SmartScreen cảnh báo với mọi ứng dụng lạ chưa mua chứng chỉ. Bạn có thể tự kiểm chứng
bằng SHA256 ở trên.
</details>

<details>
<summary><b>Có thu thập dữ liệu của tôi không?</b></summary>

Không. Các tool miễn phí xử lý hoàn toàn trên máy bạn, không gửi file đi đâu. App chỉ ra Internet
để kiểm tra cập nhật và để xử lý thanh toán khi bạn chủ động mua tool Pro.
</details>

<details>
<summary><b>Free thật hay dùng vài lần rồi đòi tiền?</b></summary>

Free thật, vĩnh viễn, không giới hạn số lần dùng, không watermark. Chỉ 2 tool Pro là trả phí,
**$5 mua đứt một lần**, không subscription.
</details>

<details>
<summary><b>Mua tool Pro thanh toán thế nào?</b></summary>

Qua LemonSqueezy (thẻ quốc tế). Bạn nạp ví trong app (tối thiểu $5) rồi dùng số dư mở khoá tool.
Mức nạp tối thiểu bằng đúng giá 1 tool nên không bị kẹt tiền lẻ. Số dư không hết hạn.
</details>

<details>
<summary><b>Cập nhật thế nào?</b></summary>

App tự kiểm tra bản mới và báo trong app. Bạn bấm đồng ý thì nó mới tải và cài —
không bao giờ tự động cài sau lưng bạn.
</details>

---

## Changelog

### v0.3.4 — 2026-07-17 — Money-safety & license hardening

**Bảo mật**
- Trình dọn ổ đĩa trên Windows không còn có thể bị lừa để chạy lệnh với quyền Administrator.
- Tool đã mua bị khoá theo tài khoản — đăng nhập tài khoản khác sẽ không dùng ké được.

**Sửa lỗi**
- Hoàn tiền một phần không còn rút cạn ví: chỉ đảo đúng phần đã hoàn.
- Nạp tiền ở khu vực có thuế/phí cộng thêm nay được cộng đúng số tiền đã chọn.
- Hết cảnh báo "Payment not detected" sai sau khi nạp thành công.

**Thay đổi**
- Số lượt cài mỗi tool được tính ở phía máy chủ nên hiển thị chính xác.

### v0.3.3 — 2026-07-16
- Tool miễn phí dành riêng cho một hệ điều hành không còn hiện nút cài trên máy sai hệ điều hành
  (App Uninstaller chỉ dành cho macOS).

### v0.3.2 — 2026-07-16
- Icon AnguLite mới, cửa hàng tool nhận biết hệ điều hành.

---

## Cần antidetect browser thật sự?

Tool **Browser Profiles** trong AnguLite quản lý các profile trình duyệt **sẵn có** trên máy bạn.
Nếu bạn cần fingerprint riêng cho từng profile, proxy tách biệt và quản lý nhiều tài khoản ở quy mô
lớn, đó là việc của **[AnguLogin](https://angulogin.com)**.

---

<sub>AnguLite được xây bằng Tauri 2 (Rust) + Angular 21 — nên installer chỉ ~10 MB và nhẹ RAM.
Đây là repo phát hành; mã nguồn ở repo riêng.</sub>
