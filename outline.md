# Đưa website lên mạng với Git + Github Page
- Chia sẻ dự án Html Css... với người khác
- Đưa link dự án vào CV tuyển dụng

# Git 
- Cần phải cài đặt trên máy tính 
- Quản lý dự án của chúng ta theo từng phiên bản khác nhau

- Trong quá trình xây dựng dự án không phải làm một lần là xong hết luôn
- Mà có thể theo từng giai đoạn
+ Giai đoạn này làm chức năng này
+ Giai đoạn khác làm chức năng khác
- Trong hành trình xây dựng dự án như vậy, cứ mỗi lần thấy dự án đã làm khá oke một chức năng nào đấy rồi
- Thì thực hiện việc commit để lưu phiên bản vào bên trong Git
- Nếu một dự án to thì sẽ có rất nhiều lần comimit ( nhiều lần lưu )
- Đồng thời sẽ có rất nhiều các phiên bản khác nhau

- Bằng cách quản lý theo phiên bản như thế này thì ta có thể quay trở lại những phiên bản trước đấy để ta có thể xem được trạng thái của dự án tại một lần commit bất kỳ

# Github
XEM SƠ ĐỒ
- Ngoài ra với Git giúp có thể làm việc nhóm
- Theo đồ sẽ có một dự án chung, có 3 người làm
- Cả 3 người này cài đặt Git trên local
- Có nghĩa trên mỗi máy tính khi lập trình cần cài Git vào để quản lý dự án
- Cả 3 người sẽ cùng join vào một tài khoản Github
- Tài khoản này sẽ là nơi lưu trữ code chung của toàn bộ hệ thống
- Trên tài khoản sẽ có một người quản lý quá trình người này làm xong sẽ đẩy lên Github và trên Github review xem code này đã oke hay chưa. Nếu oke rồi thì sẽ lưu vào trong Github 

- Ở phần hướng dẫn này ta không phải thực hành một cách tổng quan tất cả mọi thứ liên quan đến Git và Github
#1. Ta sẽ cùng nhau làm việc với bước đầu tiên là tạo ra một Git repo ( tạo ra phân vùng làm việc trên Git )
#2. Tạo ra một tài khoản ở trên Github
#3. Chuyển dự án từ trên Local ( thư mục dự án trên PC ) vào trong Git
#4. Từ Git sẽ đẩy lên Github
- Github sẽ có phần là Github Page
- Với Github Page giúp hiển thị dự án lên trên Browser một cách dễ dàng



# Chuẩn bị
1. Cài đặt Git ( Search Download Git )
2. Tạo tài khoản Github ( github.com )

# Terminal
- Kiểm tra version: git --version



# Up dự án lên mạng
1. Đưa dự án vào VSCode

2. Chạy Terminal khởi tạo một local repo ( repository )
> git init

3. Lưu code dự án vào local repo tại git

> git add .
> git commit -m 'first commit'
4. Tạo Repository trên Github

5. Đẩy dự án từ Git lên Github

> git remote add <allias> https://name-of-the-repository-link
> git push <remote> <branch-name>

6. Chạy giao diện dự án trên Github Page

