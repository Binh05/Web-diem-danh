<h1 style="color: red;">Website đang trong giải đoạn phát triển bởi công ty trách nhiệm hữu hạn 1 mình tôi</h1>

# Web điểm danh đăng nhập bằng nhận diện khuôn mặt.

## Mô rả dự án dự kiến:

* Website điểm danh sử dụng nhận diện khuôn mặt để đăng nhập theo thời gian thực.
- Trang web sẽ có các chức năng cơ bản như:
    - form đăng nhập:
        - Đăng nhập bằng tài khoản và mặt khẩu dành cho admin.
        - Đăng nhập bằng nhận diện khuôn mặt cho admin và user.
        - Không có chức năng đăng ký, tài khoản user sẽ được tạo bởi admin (do website hướng đến sử dụng nội bộ của tổ chức).
- Các chức năng dự kiến sẽ phát triển (chưa lên ý tưởng chia form):
    - Admin tạo lịch gồm các buổi điểm danh. Trong đó admin sẽ tạo các buổi điểm danh trong tuấn với người điểm danh và những người cần điểm danh, người điểm danh sẽ là user. Khung giờ bắt đầu và kết thúc được phép điểm danh theo thời gian thực. Sau thời gian này user sẽ không thể điểm danh được nữa và hệ thống sẽ ghi nhận chưa điểm danh. Khi điểm danh, user sẽ tích vào các checkbox để đánh dấu là có mặt.
    - Admin có thể xem lại các buổi điểm danh, mở gia hạn điểm danh và trích xuất file excel.
## Review Giao diện

is comming

## Công nghệ

### Frontend

- [Vite](https://vite.dev/)
- [Reactjs](https://react.dev/)
- [React-router-dom](https://reactrouter.com/)
- [Tailwind css](https://tailwindcss.com/)
- [postcss/autoprefixer](https://postcss.org/)
- [clsx](https://www.npmjs.com/package/clsx)

### Backend

iscoming


## Cách clone dự án

#### Đảm bảo trên máy đã cài Nodejs và có TDE phù hợp.

- Mở visual studio/TDE khác tùy chọn ở thu mục muốn clone
- Chạy lệnh sau trên Terminal:
```
git clone https://github.com/Binh05/Web-diem-danh.git
```
- Di chuyển vào thư mục FE bằng lệnh:
```
cd FE
```
- Trên Terminal chạy lệnh:
```
npm i
```
- Tiếp tục chạy lệnh:
```
npm run dev
```
- Truy cập link localhost để xem frontend dự án.