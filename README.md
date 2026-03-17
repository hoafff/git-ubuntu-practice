"# git-ubuntu-practice" 


1. Cài Git trên Ubuntu

Mở terminal và chạy:

sudo apt update
sudo apt install git
git --version

Mục đích:

cập nhật danh sách gói

cài Git

kiểm tra Git đã cài thành công chưa

2. Cấu hình Git lần đầu

Sau khi cài xong, thiết lập tên và email:

git config --global user.name "Nguyen Hoa"
git config --global user.email "saveme456789@gmail.com"

Kiểm tra lại:

git config --list

Mục đích:

để mỗi lần commit, Git biết ai là người tạo commit đó
3. Chuẩn bị tài khoản GitHub

Bạn cần:

có tài khoản GitHub

đăng nhập được

tạo được một repository mới

Ví dụ repo của bạn hiện là:
git-ubuntu-practice
4. Chuẩn bị môi trường làm việc trên máy

Thường gồm:

Ubuntu

VS Code

Terminal trong VS Code

thư mục project để thực hành Git

Ví dụ:

mkdir git-ubuntu-practice
cd git-ubuntu-practice
code .
5. Khởi tạo repo local để bắt đầu thực hành

Tạo file thử và khởi tạo Git:

echo "# git-ubuntu-practice" > README.md
git init

Mục đích:

tạo project local

bắt đầu biến thư mục đó thành một Git repository