BT:Khi khởi tạo git(git init ), git sẽ tạo 1 folder .git. 
Mọi người cho biết tác dụng của folder này là gì? 
Giả sử, nếu xoá hoặc di chuyển folder này sang 1 thư mục khác thì điều gì sẽ xảy ra.
Giải thích tại sao?
BL:
Khi ta khởi tại git (git init), git sẽ tạo 1 folder .git.
 Folder này dùng dể lưu dữ trạng thái cũng như tất cả dữ liệu củatất cả cái file trong thư mục đó.
 Khi ta xóa hoặc chuyển folder này thì sẽ không thể sử dụng các câu lệnh của git.
 Bắt buộcta phải khởi tạo git mới $ git init khi đó t mới có thể sử dụng git trong file này.