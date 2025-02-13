# BOOKSTORE

### Các công nghệ sử dụng:

<<<<<<< HEAD
-   ReactJS, Node.js, Express.js, MongoDB, Bootstrap

### Môi trường chạy dự án: Node.js v16.13.1

### Lý thuyết:

-   Nghiên cứu và tìm hiểu về công nghệ sử dụng trong dự án: ReactJS, NodeJS, MongoDB, Express Framework.

-   Khảo sát các công nghệ hiện tại trong việc xây dựng và phát triển hệ thống quản lý cửa hàng sách trực tuyến.

-   Tìm hiểu về các nguyên lý RESTful API và ứng dụng của chúng trong phát triển hệ thống web.

-   Nghiên cứu về các công cụ hỗ trợ như thanh toán trực tuyến và cách tích hợp chúng vào hệ thống.

-   Tìm hiểu về các phương pháp quản lý dự án và phát triển phần mềm trong môi trường thương mại điện tử.

-   Phân tích yêu cầu người dùng để xác định các tính năng chính của hệ thống.

### Thực hành:

-   Sử dụng NodeJS xây dựng Backend, triển khai API cho các chức năng như đăng ký, quản lý tài khoản, giỏ hàng, thanh toán, v.v...

-   Kết nối MongoDB để lưu trữ dữ liệu và sử dụng JWT cho xác thực người dùng.

-   Thiết kế Frontend với ReactJS, hỗ trợ các chức năng: tìm kiếm sách, đặt hàng, quản lý giỏ hàng.

-   Tích hợp hệ thống thanh toán trực tuyến để hỗ trợ khách hàng thanh toán một cách thuận tiện.

-   Xây dựng hệ thống phân quyền rõ ràng để đảm bảo quản lý một cách hiệu quả.

-   Quản lý sách, đơn hàng, khách hàng và các chương trình khuyến mãi cho quản trị viên.
=======
ReactJS, Node.js, Express.js, MongoDB, Bootstrap

### Môi trường cài đặt và công nghệ sử dụng:

Website được xây dựng trên nền tảng ReactJS và NodeJS trong môi trường phần mềm Visual Studio Code. Các công nghệ sử dụng bao gồm:

-   Frontend:

    -   ReactJS: Sử dụng cả React Hooks và React Class Components để xây dựng giao diện người dùng. ReactJS giúp xây dựng các giao diện động và dễ dàng quản lý trạng thái.

    -   Bootstrap: Thư viện giao diện người dùng giúp xây dựng các thành phần đẹp mắt và dễ sử dụng với thiết kế hiện đại.

    -   HTML, CSS, Javascript: CSS được sử dụng để viết mã CSS một cách có cấu trúc và dễ bảo trì, trong khi JavaScript được dùng cho các logic xử lý trên client-side.

-   Backend:

    -   NodeJS: Được sử dụng để xây dựng server-side của ứng dụng, với khả năng xử lý đồng thời rất hiệu quả.

    -   ExpressJS: Framework hỗ trợ việc xây dựng các API RESTful đơn giản và dễ hiểu trên nền tảng NodeJS.

    -   RESTful API: Backend triển khai các API RESTful để frontend và backend giao tiếp với nhau thông qua các HTTP requests (GET, POST, PUT, DELETE).

-   Cơ sở dữ liệu:

    -   MongoDB: Dùng để lưu trữ dữ liệu ứng dụng. MongoDB là cơ sở dữ liệu NoSQL, phù hợp với mô hình dữ liệu linh hoạt và mở rộng.

    -   Mongoose: Là thư viện ODM (Object Data Modeling) được sử dụng để giao tiếp với MongoDB. Mongoose giúp dễ dàng tạo và quản lý các schema và model, giúp thao tác với dữ liệu MongoDB trở nên thuận tiện và an toàn.

    -   Schema: Định nghĩa cấu trúc của các document trong MongoDB.

    -   Model: Các đối tượng tương ứng với các schema trong cơ sở dữ liệu, giúp thực hiện các thao tác CRUD (Create, Read, Update, Delete).

### Về tính năng của hệ thống:

-   Đăng ký và quản lý tài khoản: Người dùng có thể đăng ký, cập nhật thông tin, đổi mật khẩu và khôi phục mật khẩu qua email. Quản trị viên có thể quản lý tài khoản (thêm, sửa, xóa, khóa/mở khóa).

-   Quản lý sách: Quản trị viên có thể thêm, sửa, xóa thông tin sách. Người dùng có thể tìm kiếm sách theo nhiều tiêu chí khác nhau.

-   Quản lý giỏ hàng: Người dùng có thể thêm, xóa, cập nhật số lượng sách trong giỏ hàng.

-   Thanh toán: Hệ thống hỗ trợ phương thức thanh toán khi nhận hàng (COD), giúp khách hàng dễ dàng thanh toán khi nhận sản phẩm.

-   Quản lý đơn hàng: Người dùng có thể xem lịch sử đơn hàng, quản trị viên có thể quản lý và cập nhật trạng thái đơn hàng.

-   Quản lý khuyến mãi: Quản trị viên có thể tạo và quản lý các chương trình khuyến mãi, áp dụng cho các đơn hàng.

-   Phân quyền người dùng: Quản trị viên có toàn quyền quản lý hệ thống, người dùng chỉ xem được thông tin cá nhân và lịch sử đơn hàng.

### Giao diện website

-   Giao diện trang chủ
    ![Giao diện trang chủ](src/assets/1.PNG)

-   Giao diện quản lý của quản trị viên
    ![Giao diện admin](src/assets/2.PNG)

### Link dự án

Link FE: https://github.com/thquan0308/React-Bookstore

Link BE: https://github.com/thquan0308/NodeJS-Bookstore

### Các bước cài đặt:

-   Cài đặt ứng dụng ReactJS: Gõ lệnh

npm install
npm start

-   Các phiên bản sử dụng:

Node version v16.13.1

Npm version 8.1.2
>>>>>>> cd550cf (Recreate README.md)
