# Lịch sử thay đổi / Changelog

## [0.7.1] - 2026-09-11

### Tiếng Việt

#### Sửa lỗi

- Sửa thao tác nhấp đúp thanh tiêu đề trên Windows: phóng to và khôi phục luân phiên đúng, giữ kích thước cửa sổ trước khi phóng to.
- Xử lý đúng lệnh thanh tiêu đề do Chromium gửi, tránh đảo trạng thái thêm lần nữa.

### English

#### Fixed

- Fix repeated Windows title-bar double-clicks to alternate correctly between maximize and restore while preserving the previous window bounds.
- Handle Chromium caption system commands without toggling the resulting state a second time.

## [0.7.0] - 2026-09-11

### Tiếng Việt

#### Thêm mới

- Bộ cài Windows x64 và hỗ trợ cập nhật qua GitHub Releases.
- Tự kiểm tra, tải bản cập nhật trong nền; người dùng chủ động khởi động lại để cài đặt.
- Hiển thị chỉ số sinh tồn và tăng trưởng bên dưới minimap trong game.

#### Thay đổi

- Nhóm bộ lọc thực vật/trái cây và thức ăn động vật có thể thu gọn, hỗ trợ chọn cả nhóm.
- Hiển thị thông báo rõ ràng khi chưa cấu hình danh bạ voice công khai.

#### Sửa lỗi

- Nhấp đúp thanh tiêu đề trên Windows để phóng to hoặc khôi phục cửa sổ app trong suốt.

#### Giới hạn hiện tại

- Voice công khai cần dịch vụ máy chủ tương thích đã triển khai.
- Chưa hỗ trợ giải mã vị trí trực tiếp bằng Npcap.

### English

#### Added

- Windows x64 installer and GitHub Releases update support.
- Automatic update checks and background downloads with explicit restart/install.
- In-game survival and growth display beneath the minimap.

#### Changed

- Collapsible plant/fruit and animal food filter groups with bulk selection.
- Clear setup notice when the public voice directory is not configured.

#### Fixed

- Windows title-bar double-click maximizes and restores the transparent app window.

#### Known limitations

- Public voice requires a deployed compatible service.
- Live Npcap position decoding is not available.
