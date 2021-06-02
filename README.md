Hi mn, rất vui khi được làm việc với mn nè
Để dễ dàng hơn trong project thì phiền mọi người làm vài điều sau nha:
1. Tạo nhánh riêng rồi hãy code. Để tạo nhánh riêng , mn chạy các lệnh sau:
- git checkout develop
- git pull 
=> 2 câu lệnh này là để pull toàn bộ code trên develop về, tránh sự conflict ít nhất có thể khi code á
- git branch + tên nhánh
- git checkout + tên nhánh
2. Trước khi thêm code mới , đặc biệt là push code lên thì chạy lệnh: 
-  git pull origin develop
3. Các lệnh để push code lên
- git add .
- git commit -m "tổng quan nội dung phần code mn push"
- git push --set-upstream origin  + tên nhánh HOẶC git push (cho những lần sau push)
3. Khi push code lên thì pull request cho 1 người nào đó review nhaaaaa.
4. Hết rồi á, cám ơn mn đã dành thời gian đọc những điều trên nha !
LƯU Ý:
+ Mọi phiên bản code hoàn chỉnh sau khi merge thì sẽ được merge vào develop
+ Mn nhớ checkout develop về nha
---- Nếu mn có muốn gửi gấm gì với nhau khi code thì mn có thể viết vào file này nha .  Cám ơn mn đã đọc file <3
 