# PHP Training Outline For Intern

__Tài liệu này dùng để làm outline training cho sinh viên thực tập WEB PHP và định hướng cũng như dựa vào đó
để đánh giá các kiến thức sinh viên cần nắm được. Cuối mỗi tuần training Mentor cũng có thể phỏng vấn sinh
viên theo các đề mục trong tài liệu này.__

----

## Giới thiệu.
Giới thiệu cho sinh viên tìm hiểu về PHP/Mysql/Laravel, Restful API/webservice và xây dựng một số web app nhỏ.
Lộ trình training này sẽ kéo dài trong khoảng 1.5-2 tháng.

Trong khoảng thời gian này sinh viên sẽ được được định hướng và hướng dẫn tìm hiểu về kiến thức PHP & Mysql & frontend
và các kiến thức liên quan đến lập trình web và làm 2 project nhỏ và có thể cân nhắc cho tham gia 1 phần vào các
dự án thật của công ty hay cân nhắc tuyển dụng các bạn có kết quả thực tập tốt và có nguyện vọng làm việc ở công ty.

### Outline.
* Tuần 1: sinh viên sẽ tìm hiểu về PHP cơ bản và PHP dùng trong web.

* Tuần 2: sẽ hướng dẫn các bạn xây dựng 1 framework MVC cở bản bằng PHP và xây dựng 1 blog nhỏ trên
          Framework vừa xây dựng.

* Tuần 3 bắt đầu tìm hiếu về laravel cở bản.

* Tuần 4 trở đi vẫn tìm hiều về laravel và bắt đầu làm project thứ 2 về xây dựng 1 trang chia sẻ, đánh giá
          Ebook.

* Phần Mysql, Html, CSS, JS sẽ được các mentor giới thiệu xen vào các tuần training mà không có 1 thời gian
    cố định cho phần này.

** Outline trên là cho các bạn biết lập trình và chưa từng hay làm viêc với PHP, trong quá trình training
không nhất thiết phải theo outline trên 1 cách máy móc. Nếu mentor thấy sinh viên đã có kiến thức căn bản
thì có thể lựa chọn các phần bắt đầu phù hợp tương ứng **

----

## Content.
Phần này sẽ list ra các mục sinh viên cần tìm hiểu và nắm được.

### Tuần 1. Tìm hiểu về PHP và PHP dùng trong web.

----
Tài liệu tham khảo và training cho phần này.
Sinh viên dựa vào các đề mục cần tìm hiểu ở trên vào trang này đọc tài liệu theo mục lục của từng phần. Nếu bạn nào ko đọc được tiếng anh có thể dùng tính năng
dịch trang của google.

Trang này gồm các tài liệu về PHP7, MySql, Html, CSS, Bootstrap, JS nội dung và cách trình bày khá tốt, các mentor cũng có thể đưa ra
hoặc đưa thêm các tài liệu khác sao cho phù hợp là được.

1. [Tutorialrepublic](https://www.tutorialrepublic.com/php-tutorial/)
2. [TutorialPoint](https://www.tutorialspoint.com/php/)
3. [MySqlTutorial](http://www.mysqltutorial.org)

#### Basic PHP. (1 buổi)
1. Cài đặt môi trường thực hành và cách chạy 1 trương trình php từ môi trường thực hanh.
    Lựa chọn cách đơn giản cho các bạn sinh viên nhất, tránh việc cài đặt môi trường thực hành phức tạp ảnh hưởng đến motivation của sinh viên).

2. Cấu trúc 1 file và syntax trong PHP.

3. bến (variable) và cách khai báoc.

4. Các kiểu dữ liệu cơ bản trong PHP (scale types, collection types)

5. Các phép toán số học và logic.

6. Các control structure(if, for, foreach, switch).

7. Hàm trong PHP.

8. Variable Scope.

9. Trương trình dụng nhiều file PHP.

#### PHP Intermediate (2 buổi).

1. Class.

2. Property.

3. Method.

4. Static Properties and Methods.

5. Class constant.

6. Access Modifier.

7. Abstract class & interface.

8. Encapsulation.

9. Inheritance.

10. Polymorphism.

11. Namespce.

12. Error Handling và Exception.

13. PHP Magic constant.

14. Trait.

15. Date time.


#### PHP Dùng trong web (1 buổi).
1. HTTP Requests and PHP $_GET, $_POST.

2. PHP form data

3. Session, Cookie.

4. Validate form.

5. Upload file.

6. PHP database (PDO).

#### Advanced PHP (Phần này list ra các phần cho sinh viên tự tìm hiểu thêm)
1. PHP Standard Libraries.
    * Tìm hiểu về các hàm, class trong php để thao tác với array, datatime, file, ...,

2. Design Pattern.
    * Tìm hiểu về design pattern và các implement 1 số pattern dùng PHP.

#### PHP Package Manager (Composer)
1. Cài đặt composer.

2. Các dùng composer và autoload file php theo chuẩn PSR-4.

3. Cách tạo 1 project và cấu trúc 1 project dùng composer theo chuẩn PSR-4.


----

### Tuần 2.
Hướng sinh viện xây dựng 1 framework MVC cơ bản để sinh viên hiểu được MVC pattern rất hay dung trong
làm WEB, hiểu và nắm được các thành phần của web để khi tiếp cận các framework khác hay học framework
mới sẽ rễ hiểu và đơn giản hơn.

Tài liệu training có thể tham khảo ở đây.

[Simple PHP MVC Framework](https://github.com/phuc-ngo/php-simple-mvc)

Tài liêu Tham khảo về design pattern

1. [Source Making](https://sourcemaking.com/design_patterns)
2. [Original Design Pattern Book](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8)
3. [Design Patterns in PHP and Laravel](http://www.apress.com/it/book/9781484224502)

----

Yêu cầu của framework build cần có.

* Cấu trúc project theo chuẩn PSR-4.
* FrontController.
* Controller.
* Model.
* View.
* Database.
* Config.

**Structure**
```
├── app
│   ├── Config
│   ├── Controllers
│   ├── Core
│   ├── Models
│   ├── Services
│   ├── Utils
│   └── Views
├── bootstrap
│   └── app.php
├── composer.json
├── public
│   └── index.php
├── readme.md
└── vendor
    ├── autoload.php
    └── composer
```

Các yêu cầu thêm không bắt buộc.

* Encrypt cookie, session.
* Thử tích hợp các component/libraries khác vào framework vừa build (vd: tích hợp laravel eloquent ORM, hay validator, ...)

Nếu còn thời gian sẽ cho sinh viên xây dựng 1 blog CRUD đơn giản trên framework vừa xây dựng.

----

Từ tuần 3 sinh viên sẽ chuyển sang tìm hiểu về framework laravel. Yêu cầu là sinh viên phải học qua và nắm được
các kiến thức cở bản trong phần training 1. Nếu bạn nào chưa nắm vững thì cho tự tìm hiểu lại và thời gian sẽ rút xuống 1/2 nghĩa là còn 1 tuần cho
việc review phần 1.

### Tuần 3:

Tài liệu training larvel cũng dựa vào các đề muc cần tìm hiểu và tìm hiểu ở các trang dứoi đây hay mentor có thể dùng các tài liệu khác phù hơp.

1. Web:
* [Larvel Official Documentation](https://laravel.com/docs/5.5)
* [Laravel documentation tiếng việt](http://giaphiep.com/docs/5.3/installation)

2. Ebook:
* [Beginning Laravel A beginners guide to application development with Laravel](http://www.apress.com/br/book/9781484225370)
* [Matt Stauffer Laravel Up and Running A Framework for Building Modern PHP Apps](http://shop.oreilly.com/product/0636920044116.do)

#### Laravel basic. (2 buổi)
1. Cài đặt môi trường phát triển dùng vagrant hoặc docker nếu môi trường ở phần training 1 không chạy được
    laravel.

2. Các tạo 1 project laravel.

3. Tìm hiểu về files/folders structure của 1 project laravel.

4. Tìm hiểu về Routing.

5. Tìm hiểu về Controller class.

6. Tìm hiểu về View balde.

7. Request & Response.

#### Laravel Intermediate (2-3 buổi)
1. Tìm hiểu về config trong laravel, config môi trường, database,...,.

2. Validation.

3. Tìm hiểu về Database

4. Database migration.

5. Tim hiểu về ORM eloquent.

6. Kết hợp Model, View, Controller. Port lại blog ở phần training 1 sang dùng laravel.

7. Session & Cookie


#### Laravel Advanced. (Phần này sẽ cân nhắc để sinh viên tự tìm hiểu rồi viết báo cáo hay sẽ training)
1. Tìm hiểu về Authentication & Authorization.


4. Cache.

5. Queue

6. Restful API and webservice.

7. Eloquent Relations and (N+1) problem in ORM relation.

9. Query Builder, Scope, ...

8. Middleware, Contract, Facade.

10. Event, Broadcasting

11. Task & Scheduling


### Tuần 4.
Từ tuần này sinh viên vẫn tiếp tục học laravel và kết hợp làm project cuối. đự định cho làm 1 trang chia sẽ và đánh giá ebook gồm các chức năng.

* Trang chủ list ra các ebook đã được chia sẻ, thông tin tóm tắt về sách như:
    * Tên sách.
    * Cover.
    * ISBN
    * Author.
    * Publisher.
    * Editor.
    * Rating.
    * Comment count.
    * TDB.
* Có trang detail khi click vào sách và cho phep rate, comment.
* Rating và comment backend phải build Rest API và frontend dùng ajax.
* Cho phép tìm kiếm sách theo tên hay tên tác giả.
* Cho phép sort theo lượng rating, hay lượng comment.
* Có trang quản lý của user nếu đang nhập cho phép thêm sửa xoá, ẩn,...,.
* Có trang quản lý của hệ thống để thống kê và quản lý sách của tất cả các user gồm xoá sách, band user,...

* Các chức năng sẽ họp với team training để thông nhất spec và wireframe sau.

** Yêu cầu khi làm project thì sinh viên sẽ phải tạo nhóm thảo luận spec, đưa ra giải pháp, thiế kế DB, project structure
Rồi họp với mentor trước khi bắt đầu làm. Làm project thì có thể cho làm theo nhóm hay làm cá nhân tuỳ theo mentor quyết định
nhưng họp thảo luận phần tích spec và solution nên khuyến khích các bạn làm theo nhóm**


----

LICENSE: MIT.

This document is under MIT license, feels free to fork or send me MR for improvement,...,

