# Phoma Companion

Phoma Companion is the Android-side component for connecting a phone to Phoma
without enabling Developer options, USB debugging, or Wireless debugging.

APK releases use tags named `companion-v<version>`. They are intentionally not
marked as GitHub's latest release because this repository also hosts the Phoma
desktop installer.

## Release notes

### v0.1.1 — 2026-11-26

**English**

- **Release**: Phoma Companion is now published from Phoma's new home on GitHub, [github.com/phomaapp/phoma-release](https://github.com/phomaapp/phoma-release). The app itself works the same as in 0.1.0.

**Tiếng Việt**

- **Phát hành**: Phoma Companion giờ được phát hành từ địa chỉ mới của Phoma trên GitHub, [github.com/phomaapp/phoma-release](https://github.com/phomaapp/phoma-release). Bản thân ứng dụng vẫn hoạt động như ở 0.1.0.

### v0.1.0 — 2026-11-16

**English**

- **Initial technical preview**: pair through a Phoma link and connect to Phoma over an encrypted outbound connection without enabling ADB debugging.
- **Device control**: after explicitly enabling the Phoma accessibility service, the companion can inspect the visible interface and perform taps, swipes, text entry, Android global actions, app launches, and screenshots on supported Android versions.
- **Early integration stage**: this release provides the phone-side protocol; the Phoma desktop driver and production device-credential exchange are still being built.

**Tiếng Việt**

- **Bản thử nghiệm kỹ thuật đầu tiên**: ghép nối bằng liên kết Phoma và kết nối ra ngoài qua kênh mã hóa mà không cần bật gỡ lỗi ADB.
- **Điều khiển thiết bị**: sau khi người dùng chủ động bật dịch vụ trợ năng Phoma, Companion có thể đọc giao diện đang hiển thị và thực hiện chạm, vuốt, nhập chữ, thao tác hệ thống Android, mở ứng dụng và chụp màn hình trên các phiên bản Android được hỗ trợ.
- **Đang ở giai đoạn tích hợp sớm**: bản này cung cấp giao thức phía điện thoại; driver Phoma desktop và cơ chế cấp thông tin xác thực thiết bị dùng cho production vẫn đang được xây dựng.
