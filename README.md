# RGAME ISLE OVERLAY

[Tiếng Việt](#tiếng-việt) · [English](#english)

## Tiếng Việt

Ứng dụng đồng hành trên Windows dành cho The Isle: bản đồ, ghi chú, theo dõi chỉ số và voice nhóm.

### Tải ứng dụng

Tải bộ cài `.exe` tại [Releases](https://github.com/andy13vn/rgame-isle-public-overlay/releases). Chạy bộ cài, sau đó mở **RGAME ISLE OVERLAY**.

### Cập nhật tự động

Bản đã cài tự kiểm tra khi khởi động và định kỳ trong lúc chạy. Bản mới được tải nền; vào **Cài đặt → Cập nhật ứng dụng → Khởi động lại và cài đặt** khi chơi xong. App không tự ngắt phiên chơi để cài cập nhật.

Các tệp được tải lên mỗi bản phát hành:

- Bộ cài Windows x64 `.exe`.
- `latest.yml`: thông tin phiên bản và mã kiểm tra tải xuống cho hệ thống cập nhật.

Không cần tải `latest.yml` bằng tay. Repo này chỉ dùng phân phối tài liệu và bản phát hành, không chứa mã nguồn ứng dụng. Hai mục **Source code (zip/tar.gz)** do GitHub tự tạo chứa nội dung repo public tại tag tương ứng, không chứa mã nguồn riêng của app.

### Phạm vi hiện tại

- Overlay hiển thị khi cửa sổ game đang hoạt động; cửa sổ quản lý hoạt động như ứng dụng Windows.
- Dữ liệu chỉ số phụ thuộc nguồn dữ liệu được kết nối; dữ liệu thiếu hoặc cũ được hiển thị là không khả dụng.
- Voice cần máy chủ tương thích được cấu hình. Repo cập nhật không phải dịch vụ danh bạ voice.
- Chưa hỗ trợ giải mã vị trí trực tiếp bằng Npcap.

Xem [lịch sử thay đổi song ngữ](CHANGELOG.md).

## English

A Windows companion for The Isle with maps, personal markers, survival tracking and group voice.

### Download

Download the `.exe` installer from [Releases](https://github.com/andy13vn/rgame-isle-public-overlay/releases). Run the installer, then open **RGAME ISLE OVERLAY**.

### Automatic updates

Installed builds check for updates on startup and periodically while running. New versions download in the background. When you finish playing, open **Settings → App updates → Restart and install**. The app does not automatically interrupt your game session to install updates.

Files uploaded for each release:

- The Windows x64 `.exe` installer.
- `latest.yml`: version information and download checksums used by the updater.

You do not need to download `latest.yml` manually. This repository distributes documentation and releases only; it does not contain the application's source code. GitHub automatically generates the **Source code (zip/tar.gz)** links from the public repository at the corresponding tag. Those archives do not contain the app's private source code.

### Current scope

- The overlay appears while the game window is active; the management window behaves like a normal Windows application.
- Survival readings depend on the connected data source. Missing or stale readings are shown as unavailable.
- Voice requires a configured compatible server. This update repository is not a voice directory service.
- Live position decoding through Npcap is not available.

See the [bilingual changelog](CHANGELOG.md).
