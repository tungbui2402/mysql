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
- Host: Địa chỉ IP hoặc tên miền của server.
- Port: Cổng mà server lắng nghe kết nối.
- Username: Tên đăng nhập để truy cập vào hệ thống.
- Password: Mật khẩu để truy cập vào hệ thống.
- Database name: Tên của cơ sở dữ liệu mà ứng dụng sử dụng.
- Timeout: Thời gian tối đa cho phép để thực hiện một yêu cầu kết nối hoặc xử lý dữ liệu.
- Cache size: Kích thước bộ đệm cho phép lưu trữ dữ liệu tạm thời.
- Logging level: Mức độ chi tiết của các thông báo ghi nhật ký (log) được tạo ra bởi ứng dụng.
- Debug mode: Chế độ gỡ rối (debug) cho phép hiển thị thông tin chi tiết về các lỗi và vấn đề trong quá trình chạy ứng dụng.
- SSL: Cấu hình cho phép sử dụng SSL (Secure Socket Layer) để bảo vệ các kết nối mạng giữa ứng dụng và server.
- Session timeout: Thời gian tối đa cho phép một phiên làm việc của người dùng trước khi bị đóng.
- Maximum upload size: Kích thước tối đa cho phép của các tệp tin được tải lên lên server.
- Default language: Ngôn ngữ mặc định cho ứng dụng.

#### 5.1. Cấu hình để cho phép connect đến mysql từ 1 server khác.
Để cho phép kết nối với MySQL từ một máy chủ khác, bạn cần đặt tham số cấu hình `bind-address` thành địa chỉ IP của máy chủ MySQL hoặc thành `0.0.0.0` trong tệp cấu hình MySQL và đảm bảo rằng tường lửa trên máy chủ được định cấu hình để cho phép kết nối với cổng 3306 (hoặc một cổng khác nếu bạn đã thay đổi cấu hình).

#### 6. Mô hình Master-Slave
Mô hình master-slave là một kiểu cấu trúc hệ thống gồm hai hoặc nhiều server trong đó một server được chỉ định làm master và các server khác được chỉ định làm slave. Trong mô hình này, dữ liệu được đồng bộ hóa giữa master và slave bằng cách sao chép dữ liệu từ master đến các slave.
Mô hình master-slave thường được sử dụng trong các hệ thống cần đảm bảo tính sẵn sàng và độ tin cậy cao, ví dụ như các hệ thống cơ sở dữ liệu hoặc các hệ thống web quy mô lớn.
Các đặc điểm của mô hình master-slave bao gồm:
- Master là nơi lưu trữ và quản lý dữ liệu.
- Slave đồng bộ dữ liệu từ master và sử dụng dữ liệu sao chép để phục vụ các yêu cầu từ người dùng.
- Khi dữ liệu trên master thay đổi, các slave sẽ được cập nhật để đồng bộ hóa dữ liệu.
- Slave có thể được sử dụng để xử lý các yêu cầu đọc dữ liệu, giảm tải cho master và tăng hiệu suất hệ thống.
Mô hình master-slave có nhiều ưu điểm như tính sẵn sàng và độ tin cậy cao, khả năng mở rộng dễ dàng, giảm tải cho master và tăng hiệu suất hệ thống. Tuy nhiên, nó cũng có một số hạn chế như chi phí cao do cần nhiều server, sự đồng bộ hóa dữ liệu không được tức thời và phải đảm bảo tính nhất quán của dữ liệu trên master và các slave.

#### 6.1. Master-Slave trong MySQl
Hệ thống sẽ có 2 (hoặc nhiều hơn) database giống hệt nhau, mỗi database được cài trên 1 server khác nhau. Trong số các db đó, có 1 db được gọi là master (ông chủ), các db còn lại được gọi là slave (nô lệ). Khi db master xảy ra một sự kiện làm thay đổi dữ liệu (thêm, sửa, xóa) thì db master sẽ log ra một file, các db slave thì liên tục lắng nghe file log này, và thực hiện việc thay đổi dữ liệu trên db slave như thay đổi trên db master.
Mô hình Master-Slave trong MySQL có nhiều ứng dụng trong việc tăng tính sẵn sàng và độ tin cậy của hệ thống. Ví dụ, nếu có sự cố xảy ra trên Master, các máy chủ Slave vẫn có thể sử dụng dữ liệu được sao chép từ Master để tiếp tục hoạt động. Ngoài ra, mô hình Master-Slave trong MySQL cũng có thể được sử dụng để phân tải tải cho các máy chủ Slave, giúp tăng hiệu suất cho hệ thống.

#### 6.2. Ưu và nhược điểm của mô hình master-slave trong mysql
Ưu điểm của mô hình Master-Slave trong MySQL:
- Tăng tính sẵn sàng và độ tin cậy của hệ thống: Khi có sự cố xảy ra trên Master, các máy chủ Slave vẫn có thể sử dụng dữ liệu được sao chép từ Master để tiếp tục hoạt động.
- Phân tải tải cho các máy chủ Slave: Mô hình Master-Slave trong MySQL có thể được sử dụng để phân tải tải cho các máy chủ Slave, giúp tăng hiệu suất cho hệ thống.
- Sao lưu và phục hồi dữ liệu dễ dàng: Khi Master bị lỗi, bạn có thể sử dụng một Slave khác làm Master để tiếp tục vận hành hệ thống.
Nhược điểm của mô hình Master-Slave trong MySQL:
- Không hỗ trợ đọc/ghi đồng thời: Khi có nhiều Slave, các Slave chỉ có thể đọc dữ liệu từ Master, không thể ghi dữ liệu vào Master.
- Tốn kém chi phí: Mô hình Master-Slave trong MySQL yêu cầu có nhiều hơn một máy chủ để triển khai, do đó, nó tốn kém chi phí hơn so với một máy chủ đơn.
- Độ trễ tương đối cao: Do dữ liệu phải được sao chép từ Master đến Slave, do đó, có thể có độ trễ tương đối cao giữa các Slave và Master, ảnh hưởng đến hiệu suất của hệ thống.
