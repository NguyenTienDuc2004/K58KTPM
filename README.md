# K58KTPM
bài tập 2 k225480106081 Nguyễn Tiến Đức môn hệ quản trị cơ sở dữ liệu
DEADLINE: 23H59 NGÀY 25/03/2025
## ĐIỀU KIỆN: (ĐÃ LÀM XONG BÀI 1)
Đã cài đặt SQL Server 2022 Dev.
Đã cài đặt SQL Managerment Studio bản mới nhất.
Đã kết nối từ SQL Managerment Studio vào SQL Server.
Đã có tài khoản github, biết cách tạo repository(kho lưu trữ) cho phép truy cập public.
## BÀI TOÁN:
Tạo csdl quan hệ với tên QLSV gồm các bảng sau:
SinhVien(#masv,hoten,NgaySinh)
Lop(#maLop,tenLop)
GVCN(#@maLop,#@magv,#HK)
LopSV(#@maLop,#@maSV,ChucVu)
GiaoVien(#magv,hoten,NgaySinh,@maBM)
BoMon(#MaBM,tenBM,@maKhoa)
Khoa(#maKhoa,tenKhoa)
MonHoc(#mamon,Tenmon,STC)
LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)
## YÊU CẦU:
Thực hiện các hành động sau trên giao diện đồ hoạ để tạo cơ sở dữ liệu cho bài toán:
Tạo database mới, mô tả các tham số(nếu có) trong quá trình.
Tạo các bảng dữ liệu với các trường như mô tả, chọn kiểu dữ liệu phù hợp với thực tế (tự tìm hiểu)
Mỗi bảng cần thiết lập PK, FK(s) và CK(s) nếu cần thiết. (chú ý dấu # và @: # là chỉ PK, @ chỉ FK)
Chuyển các thao tác đồ hoạ trên thành lệnh SQL tương đương. lưu tất cả các lệnh SQL trong file: Script_DML.sq
## Hinh anh pate:
![image](https://github.com/user-attachments/assets/d444ea1c-57f0-44aa-9216-6ad42df1cf94)
![image](https://github.com/user-attachments/assets/050fd1a2-d6a8-4b38-8b70-ec767ca841d5)
![image](https://github.com/user-attachments/assets/bb233203-e24b-4ef1-ad87-4dae30570124)
![image](https://github.com/user-attachments/assets/3010ab5f-63c1-4f9c-9916-6f13664188bc)
![image](https://github.com/user-attachments/assets/32282fd4-f4ef-4630-8bc2-68630dd43c61)
![image](https://github.com/user-attachments/assets/0e53080a-d883-45d1-829e-7586f03f4452)
![image](https://github.com/user-attachments/assets/287b0873-c85f-42fa-b1be-bb109a3f4b61)
![image](https://github.com/user-attachments/assets/b0fba80c-0618-4248-ba35-bbcf11a2f1c7)
![image](https://github.com/user-attachments/assets/f817bd4e-ca09-4e43-9383-fc0ef499227d)
![image](https://github.com/user-attachments/assets/d8b63cda-489f-40fe-b34f-b30cc432cb10)
![image](https://github.com/user-attachments/assets/db2609a8-9599-471a-ac68-33a46305dba3)
![image](https://github.com/user-attachments/assets/78336db9-04eb-4686-a123-3e2e9736df92)
![image](https://github.com/user-attachments/assets/7d31dafe-eaab-43d9-8d30-a31f3c5f6318)
![image](https://github.com/user-attachments/assets/6a594dea-9ba4-4aca-80be-f310d6de7d17)
![image](https://github.com/user-attachments/assets/5c189c2e-2f8b-4b42-8959-6467b73ce0d4)
![image](https://github.com/user-attachments/assets/c3c17e72-26c1-4bb4-8263-b69f2674b5a2)
![image](https://github.com/user-attachments/assets/b31ce285-2378-4c52-a748-6c849095c564)
![image](https://github.com/user-attachments/assets/a490366d-c383-44c0-8546-47f458c79374)
![image](https://github.com/user-attachments/assets/1a75fb76-12ba-4707-aad2-88248ff5243c)
![image](https://github.com/user-attachments/assets/eb169a9b-8e25-49f2-a3f2-c2c35b7e911e)
![image](https://github.com/user-attachments/assets/f5fe8220-7b1f-4942-bc4b-5e6ff7d45a71)
![image](https://github.com/user-attachments/assets/af735fb3-91f5-4da6-8567-29103e86edf1)























