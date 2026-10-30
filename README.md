# BÀI LÀM: XÂY DỰNG HYBRID WORKFLOW
## 1. Giải pháp
Nhóm sử dụng Local SSD kết hợp với OneDrive để bảo vệ dữ liệu.
- Local SSD: Lưu file thiết kế 3D trên máy tính.
- OneDrive: Tự động đồng bộ file lên Cloud sau khi nhấn Ctrl + S.
- Version History: Giúp khôi phục phiên bản cũ khi file bị lỗi hoặc chỉnh sửa nhầm.
## 2. Sơ đồ luồng dữ liệu
```
Designer chỉnh sửa file 3D
          ↓
      Ctrl + S
          ↓
Lưu file trên Local SSD
          ↓
     OneDrive đồng bộ
          ↓
      Lưu lên Cloud
          ↓
 Các thành viên truy cập
```


Khi mất Internet: File vẫn được lưu trên SSD. Khi có mạng trở lại, OneDrive sẽ tiếp tục đồng bộ.

Khi có xung đột phiên bản: Kiểm tra các bản file, chọn bản đúng và ổn định nhất, sau đó lưu lại thành phiên bản mới.
## 3. Cách khôi phục dữ liệu bằng Version History
1. Mở OneDrive và tìm file thiết kế bị lỗi.
2. Chọn Version History.
3. Chọn phiên bản trước đó còn hoạt động tốt và nhấn Restore.
## 4. Quy trình thiết lập cho Designer (3 bước)
Bước 1: Cài đặt OneDrive, đăng nhập và tạo thư mục PTIT_Museum để lưu file thiết kế.

Bước 2: Lưu file thiết kế trực tiếp vào thư mục OneDrive trên máy tính. Sau mỗi lần chỉnh sửa, nhấn Ctrl + S để lưu và đồng bộ.

Bước 3: Chia sẻ thư mục cho các thành viên và sử dụng Version History để khôi phục file khi cần.
5. Kết luận
Sử dụng Local SSD kết hợp với OneDrive giúp nhóm hạn chế mất dữ liệu khi máy tính gặp sự cố. Version History giúp khôi phục các phiên bản cũ khi chỉnh sửa sai. Khi mất Internet, file vẫn được lưu trên máy và sẽ đồng bộ lại khi có mạng.

Lưu ý: Trước khi tắt máy, cần kiểm tra OneDrive đã đồng bộ hoàn tất để đảm bảo file mới nhất được lưu trên Cloud.
