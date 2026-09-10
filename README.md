# RGAME ISLE OVERLAY

Ứng dụng đồng hành trên Windows dành cho The Isle: bản đồ, ghi chú, theo dõi chỉ số và voice nhóm.

## Tải ứng dụng

Tải bộ cài `.exe` tại [Releases](https://github.com/andy13vn/rgame-isle-public-overlay/releases). Chạy bộ cài, sau đó mở **RGAME ISLE OVERLAY**.

## Cập nhật tự động

Bản đã cài tự kiểm tra khi khởi động và định kỳ trong lúc chạy. Bản mới được tải nền; vào **Cài đặt → Cập nhật ứng dụng → Khởi động lại và cài đặt** khi chơi xong. App không tự ngắt phiên chơi để cài cập nhật.

Mỗi bản phát hành gồm:

- Bộ cài Windows x64 `.exe`.
- `latest.yml`: thông tin phiên bản và mã kiểm tra tải xuống cho hệ thống cập nhật.

Không cần tải `latest.yml` bằng tay. Repo này chỉ dùng phân phối tài liệu và bản phát hành, không chứa mã nguồn ứng dụng.

## Phạm vi hiện tại

- Overlay hiển thị khi cửa sổ game đang hoạt động; cửa sổ quản lý hoạt động như ứng dụng Windows.
- Dữ liệu chỉ số phụ thuộc nguồn dữ liệu được kết nối; dữ liệu thiếu hoặc cũ được hiển thị là không khả dụng.
- Voice cần máy chủ tương thích được cấu hình. Repo cập nhật không phải dịch vụ danh bạ voice.
- Không công bố hỗ trợ giải mã vị trí trực tiếp bằng Npcap.

Xem [lịch sử thay đổi](CHANGELOG.md).
