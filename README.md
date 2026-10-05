# Báo cáo Bài 2: Tái cấu trúc lịch sử bằng Interactive Rebase

## 1. Cấu hình kịch bản Rebase (Rebase Plan)
Em đã thay đổi kịch bản 4 commit cuối thành như sau:
- `pick`: Giữ nguyên commit đầu.
- `squash`: Gộp commit "fix typo" và "adds utility functions" vào commit trên.
- `drop`: Xóa bỏ hoàn toàn commit chứa file rác `temp.txt`.

## 2. Kết quả Rebase (git log --oneline)
Lịch sử đã sạch sẽ, thông điệp được gộp thành:
(Dán dòng kết quả git log --oneline của bạn vào đây)
