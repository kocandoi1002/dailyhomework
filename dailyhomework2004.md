Tìm hiểu về git branch

Khái niệm
Branch là cái dùng để phân nhánh và ghi lại luồng của lịch sử. Branch đã phân nhánh sẽ không ảnh hưởng đến branch khác nên có thể tiến hành nhiều thay đổi đồng thời trong cùng 1 repository.
khi hợp lại mà gặp vấn đề, dễ dàng tìm lỗi ở branch gặp vấn đề.
branch master:
nhánh chính trong git, có thể tưởng tượng như thân cây trong working tree hiện tại, được khởi tạo mặc định khi thực hiện commit lần đầu.
Khi tiến hành commit lần đầu trong repository thì Git sẽ tạo ra một branch có tên là master. Vì thế những lần commit sau sẽ được thêm vào branch master cho đến khi chuyển đổi branch.
Một số thao tác với git branch:
tạo branch: git branch <tên branch>
liệt kê các branch: git branch hoặc git brach --list
xóa branch: git branch -d <tên nhánh>
chuyển branch: git checkout <tên nhánh>
hợp nhất branch: git merge <tên nhánh>