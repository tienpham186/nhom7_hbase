1.Môi trường chạy
	- Sử dụng IDE Netbean 8.2
	- JDK 1.8.0_191
	- Tomcat 8.0.27.0 (Chọn cài đặt tomcat khi cài Netbean)
	- Trình duyệt web: firefox, chrome.

2.Cấu hình đến database
	- File cấu hình nằm trong thư mục chứa Project\src\java\config.properties
		+ Tham số IP_ADDRESS cấu hình địa chỉ ip cài Hbase.
		+ Tham số DB_CONNECTION/DB_USER/DB_PASSWORD cấu hình địa chỉ/user/pass của DB MySQL
	
3.Chạy ứng dụng
	- Giải nén file zip.
	- Mở Project bằng Netbean (File -> Open Project -> chọn đường dẫn tới file giải nén).
		+ Check lại cấu hình jdk (trên Panel "Project" bên phải màn hình, chuột phải vào project Hbase -> chọn Properties -> Chọn Categories là Source ->  Mục Source/Binary Format chọn JDK8)
		+ Check lại cấu hình tomcat (trên Panel "Project" bên phải màn hình, chuột phải vào project Hbase -> chọn Properties -> Chọn Categories là Run ->  Mục server chọn Apache tomcat).
	- Chạy ứng dụng:
		- Chuột phải vào project -> click run.