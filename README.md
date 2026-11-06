1 Vấn đề là gì
Git báo “fatal: not a git repository…” vì bạn đang chạy lệnh ngoài thư mục dự án Git hoặc thư mục đó chưa có .git
2 Yêu cầu đề bài
Dùng mô hình IPO để tạo prompt yêu cầu AI dịch lỗi và hướng dẫn sửa bằng tiếng Việt
- Input: Ngữ cảnh đang gõ lệnh Git và nguyên văn mã lỗi
- Process: AI giải thích lỗi, xác định nguyên nhân và sắp xếp cách kiểm tra
- Output: Bản dịch cùng 3 bước sửa lỗi
3 Cách làm
Ba bước sửa lỗi: Chạy pwd để xem vị trí hiện tại và dùng cd vào đúng thư mục dự án sau đó chạy git status để kiểm tra Nếu dự án chưa có Git
