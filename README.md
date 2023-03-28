# Mysql

#### Giới thiệu
MySQL là một hệ quản trị cơ sở dữ liệu quan hệ mã nguồn mở (open source relational database management system - RDBMS) phổ biến nhất trên thế giới. MySQL có thể hoạt động trên nhiều hệ điều hành khác nhau, bao gồm Windows, Linux và Mac OS X. Nó cũng có thể được tích hợp với các ngôn ngữ lập trình như PHP, Java, Python, Perl và các ngôn ngữ khác để phát triển ứng dụng web và phần mềm.

#### 1. Khái niệm:
Mysql là hệ thống quản trị dữ liệu phổ biến dùng để quản lý dữ liệu và được sử dụng nhiều trong các ứng dụng web như php và các hệ thống máy chủ.
#### 1.1. Ưu và nhược điểm:
- Ưu thì mysql dễ sử dụng, đa tính năng, khả năng mở rộng và tốc độ thực thi nhanh.
- Nhược thì mysql có bảo mật không cao, không hỗ trợ các tính năng và các tính năng quản lý tài nguyên.
#### 1.2. Version mới nhất và phổ biến nhất
Mysql 8.0.32 là phiên bản mới nhất hiện tại.
Mysql 5.7 là phiên bản phổ biến.

#### 2. Những thằng được tách ra từ mysql
Mysql được tách ra được nhiều csdl như mariadb, percona server, amazon aurora, google cloud sql và oracle mysql cloud service.

#### 3. Mysql thuộc loại cơ sở dữ liệu gì, có những thằng nào cùng loại, khác loại và ưu thế so với các thằng cùng loại
#### 3.1. Mysql thuộc loại cơ sở dữ liệu gì
MySQL là một hệ quản trị cơ sở dữ liệu quan hệ.
#### 3.2. Những thằng cùng loại và khác loại với mysql
Cùng loại gồm oracle, Microsoft SQL Server, PostgreSQL, SQLite, IBM DB2 và MariaDB.
Khác loại gồm  MongoDB, Cassandra, Redis, Couchbase là các cơ sở dữ liệu lưu trữ dữ liệu dưới dạng tài liệu hoặc bản ghi.
#### 3.3. Ưu thế so với các thằng cùng loại
Ưu thế của mysql so với các dữ liệu khác là nó miễn phí nên giảm chi phí đầu tư và phát triển dự án, có hiệu suất cao, có thể mở rộngđể xử lý dữ liệu, có thể chạy trên nhiều nền tảng khác như windows, linux và macOS, và có công cụ và thư viện hỗ trợ người dùng, dễ sử dụng, có độ bảo mật cao, hỗ trợ đầy đủ chuẩn sql, hỗ trợ khóa ngoại và cho phép tùy chỉnh cấu hình để phù hợp với nhu cầu của dự án.

#### 4. So sánh phiên bản 5.7 và 8.0
- Hiệu suất: MySQL 8.0 được cải tiến về hiệu suất so với MySQL 5.7. Nó có khả năng xử lý các truy vấn nhanh hơn và hỗ trợ các tính năng mới như truy vấn đệ quy và cập nhật tập trung.

- Bảo mật: MySQL 8.0 cung cấp các tính năng bảo mật mới như bảo vệ dữ liệu với mã hóa AES-256 và tự động bảo vệ chống lại các cuộc tấn công DDoS.

- Replication: MySQL 8.0 cải thiện tính năng sao chép với tính năng mới như Group Replication, một tính năng đồng bộ hóa cụm máy chủ mới cho phép sao chép đồng bộ giữa các nút cụm.

- JSON: MySQL 8.0 hỗ trợ tốt hơn cho JSON so với MySQL 5.7. Nó cung cấp các tính năng mới như các toán tử JSON, cú pháp đầy đủ JSON và các hàm mới để xử lý dữ liệu JSON.

- Tính năng mới: MySQL 8.0 cung cấp các tính năng mới như Window Functions, Recursive Common Table Expressions (CTEs) và Histograms.
#### 4.1. Những cải tiến của mysql 8.0
- Group Replication: Đây là tính năng đồng bộ hóa cụm máy chủ mới cho phép sao chép đồng bộ giữa các nút cụm. Nó cung cấp tính năng tự động phân phối dữ liệu và tăng khả năng chịu lỗi của cụm máy chủ. Group Replication cũng có khả năng tự động phát hiện và sửa chữa các lỗi.

- Recursive Common Table Expressions (CTEs): Tính năng này cho phép truy vấn đệ quy trong MySQL. Nó cho phép truy vấn dữ liệu phân cấp và phức tạp hơn trong MySQL.

- Window Functions: Đây là tính năng cho phép thực hiện truy vấn với các hàm cửa sổ như SUM, COUNT, AVG, MIN, MAX, ROW_NUMBER, RANK, DENSE_RANK, LEAD, LAG.

- Histograms: Tính năng này cung cấp các dữ liệu phân bố thống kê về giá trị của các cột trong bảng, giúp cải thiện hiệu suất truy vấn.

- Tính năng bảo mật: MySQL 8.0 cải thiện tính năng bảo mật với việc bảo vệ dữ liệu với mã hóa AES-256 và tự động bảo vệ chống lại các cuộc tấn công DDoS.

- JSON: MySQL 8.0 cải tiến tính năng sao chép và hỗ trợ tốt hơn cho JSON.

#### 5. File config trong mysql

#### 5.1. Tùy chọn cấu hình cho bộ nhớ đệm:
- key_buffer_size: Kích thước bộ nhớ đệm cho các bảng lưu trữ theo kiểu MyISAM.
- innodb_buffer_pool_size: Kích thước bộ nhớ đệm cho các bảng lưu trữ theo kiểu InnoDB.
- query_cache_size: Kích thước bộ nhớ đệm cho lưu trữ các kết quả truy vấn.
#### 5.2. Tùy chọn cấu hình cho kết nối:
- max_connections: Số lượng kết nối tối đa được phép đồng thời.
- wait_timeout: Thời gian chờ tối đa trước khi một kết nối bị đóng.
- interactive_timeout: Thời gian chờ tối đa trước khi một kết nối tương tác bị đóng.
#### 5.3. Tùy chọn cấu hình cho bảo mật:
- skip-networking: Tắt chức năng mạng để MySQL chỉ chạy trên máy chủ local.
- secure-file-priv: Định nghĩa thư mục cho các tệp tin được truy cập bởi lệnh LOAD DATA INFILE hoặc SELECT ... INTO OUTFILE.
- ssl-cert, ssl-key: Các tệp chứa chứng chỉ SSL để sử dụng cho kết nối SSL.
#### 5.4. Tùy chọn cấu hình cho ghi log:
- log_error: Định nghĩa vị trí cho tệp lưu trữ các thông báo lỗi.
- slow_query_log: Sử dụng log chậm để ghi lại các truy vấn chậm.
- log_bin: Sử dụng log nhị phân để ghi lại các hoạt động của MySQL.
#### 5.5. Tùy chọn cấu hình khác:
- default-storage-engine: Định nghĩa kiểu lưu trữ mặc định cho các bảng mới.
- default-time-zone: Đặt múi giờ mặc định cho MySQL.
- tmpdir: Định nghĩa thư mục tạm cho MySQL.

#### 6. Cài đặt
Hiện tại thì Mysql có thể sử dụng trên Win, linux trong bài viết này tôi chỉ thực hiện trên Linux.
Tôi sẽ thực hiện trên ubuntu

```
sudo apt update
sudo apt install mysql-client
sudo apt install mysql-server
```
Sau khi chạy xong ta có thể kiểm tra phiên bản của mysql

```
mysql -V
```
Sau khi kiểm tra phiên bản của mysql xong thì chúng ta tiến hành đặt mật khẩu cho root

```
sudo mysql_secure_installation 
```
![Screenshot (57)](https://user-images.githubusercontent.com/129025623/228150269-b040610d-65f9-4af6-b0cc-82e8bb937ad7.png)
