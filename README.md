# bt_moblile
# Nguyễn Hoàng Việt - K225480106074
# 1. MIT App Inventor

Bản chất: Là môi trường lập trình trực quan (Visual Programming) dựa trên trình duyệt web, cho phép xây dựng ứng dụng Android mà không cần viết mã nguồn (code) truyền thống.

Quy trình làm việc:

- Designer: Thiết kế giao diện (UI) và thiết lập thuộc tính cho linh kiện.
 
- Blocks: Lập trình logic điều khiển bằng cách lắp ghép các khối chức năng.

# Mô tả các thao tác kỹ thuật

+ Thanh công cụ (Palette): Chứa kho linh kiện đa dạng từ giao diện (Button, Label), bố cục (Layout) đến Media. Việc kéo thả giúp hiện thực hóa ý tưởng thiết kế một cách trực quan.

+ Thuộc tính (Properties): Mỗi linh kiện có các thông số (Text, Color, FontSize). Việc thay đổi này giúp định hình giao diện và đảm bảo dữ liệu nhập vào là hợp lệ (ví dụ: NumbersOnly cho TextBox).

+ Lập trình Blocks (Lập trình hướng sự kiện):

  - Bản chất: Các khối lệnh hoạt động dựa trên các "Sự kiện" (Events) – khi một hành động xảy ra (Click, Scroll), chương trình sẽ phản hồi.

  - Ưu điểm: Loại bỏ lỗi cú pháp (dấu ngoặc, chấm phẩy), dễ tiếp cận cho người mới, tốc độ xây dựng ứng dụng rất nhanh.

  - Nhược điểm: Khả năng tùy biến sâu phần cứng hạn chế hơn so với lập trình code thuần (như Java/Kotlin), khó quản lý khi dự án quá lớn.

+ Sử dụng Backpack (Ba lô): Đây là công cụ đắc lực để sao chép (copy) các khối lệnh logic dùng chung giữa nhiều màn hình khác nhau, giúp tối ưu hóa thời gian và tránh lặp lại công việc.

# Tạo project mới:

<img width="1918" height="996" alt="image" src="https://github.com/user-attachments/assets/6051e685-9650-4743-b5b2-7a679747bd3a" />

# Sử dụng các interface để kéo thả theo ý muốn và dưới đây là chi tiết 3 screen 

# Screen 1: 

<img width="1918" height="982" alt="image" src="https://github.com/user-attachments/assets/213075d3-ad63-4ad9-9f85-d38293067239" />

Màn hình 1 giới thiệu bản thân và có 2 nút truy cập đến 2 screen khác 1 là giải phép tính cộng và webview 

Bao gồm: 2 button và 1 label 

# Block screen 1: 

<img width="1913" height="1077" alt="image" src="https://github.com/user-attachments/assets/6bb608ba-2adf-4c94-9465-5bd9d00e9b5a" />

Khi ấn vào nút giải toán ở screen 1 thì sẽ => screen 2 tương tự với nút webview 

# Screen 2: 

<img width="1912" height="1078" alt="image" src="https://github.com/user-attachments/assets/d354025c-6a04-45a9-a869-367a6f75f504" />

Screen 2 là phép cộng A + B Tìm X sau đó hiển thị kết quả ở dưới và có nút Back về screen 1 

# Block screen 2: 

<img width="1242" height="473" alt="image" src="https://github.com/user-attachments/assets/b7efbcdc-062e-43b6-b2e7-9c7837076f6d" />

Khi ấn vào nút tìm X Sẽ trả về kết quả của A + B 

Nút Back là để quay lại screen 1

# Screen 3: 

<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/83bd3886-791b-4e21-8887-7580040d720f" />

Lấy webview vứt vào sau đó để đường dẫn url mà b muốn trên internet 

# Block screen 3: 

<img width="857" height="412" alt="image" src="https://github.com/user-attachments/assets/73fa7dfe-1f35-4057-922e-a1649938f62e" />

# Connect với điện thoại để test 

- Tải Mit app inventor trên đt của b về xong scan mã qr là có thể vào test đc app

<img width="1787" height="867" alt="image" src="https://github.com/user-attachments/assets/6e343d2a-0f05-4b99-8328-b5f1719452c7" />

# Test 

<img width="944" height="2046" alt="image" src="https://github.com/user-attachments/assets/ea78be07-3e4d-4d99-9502-806c488ff4df" />

<img width="944" height="2046" alt="image" src="https://github.com/user-attachments/assets/4641bd67-2b6e-4fad-aa1a-830671ba4af9" />

<img width="944" height="2046" alt="image" src="https://github.com/user-attachments/assets/1db07939-aa9b-45f5-9dc4-34387b601551" />

# 2. Android Studio 

# Tạo Project mới: 

<img width="1187" height="797" alt="image" src="https://github.com/user-attachments/assets/4f065e22-73f1-41a9-b4a5-5b7290af5e09" />


# THƯ MỤC CẦN THIẾT TRONG BÀI 

<img width="378" height="930" alt="image" src="https://github.com/user-attachments/assets/707bc9d6-4520-4188-881e-8faed36d3e7d" />


# 1. GIAO DIỆN CHÍNH (activity_app1.xml)

Đường dẫn file: app > res > layout > activity_app1.xml

DÙNG CODE ĐỂ BUILD APP THEO MONG MUỐN SAU ĐÓ SẼ HIỂN THỊ GIAO DIỆN MÔ PHỎNG Ở BÊN 

<img width="1367" height="857" alt="image" src="https://github.com/user-attachments/assets/6346b68c-b0b5-40ef-8d77-2ad8a005f154" />


# 2. CODE ĐIỀU HƯỚNG ( app1activity.java) 

Đường dẫn file: app > java > com.example.baitaplonmobile > app1activity.java

<img width="1572" height="947" alt="image" src="https://github.com/user-attachments/assets/351de3a9-924f-4ceb-af29-26db79116d84" />

Nhiệm vụ: Ánh xạ các nút bấm bằng findViewById và sử dụng đối tượng Intent để bắt sự kiện setOnClickListener, giúp chuyển đổi màn hình khi người dùng click vào từng nút.

# APP 1: (Giải toán & Đóng gói JSON gọi API) 

1. Chức năng: Nhập dữ liệu số a, b, c, nhập tên chuỗi, giải toán bậc 2, đóng gói cấu trúc dữ liệu JSON lồng nhau gửi lên Server https://k58kmt.tdh.io.vn/api và nhận mã stt trả về.Tên file giao diện: activity_app2_math.xml

<img width="1441" height="900" alt="image" src="https://github.com/user-attachments/assets/9f3ea7f6-9b69-4442-b564-3a6172469aa0" />

# 2. CODE ĐIỀU HƯỚNG (app2activity.java)

Đường dẫn file: app > java > com.example.baitaplonmobile > app2activity.java

<img width="1460" height="752" alt="image" src="https://github.com/user-attachments/assets/02959c8d-4468-4690-b729-174887959f25" />

# APP 2: WebView Tích hợp Website 

1. Đường dẫn file: app > res > layout > activity_app3_web.xmlNhiệm vụ: Sử dụng 3 ô nhập liệu EditText nhận các hệ số số thực a, b, c, kết hợp giới hạn kiểu
nhập android:inputType="numberSigned|numberDecimal" (chỉ cho phép nhập số thực và số âm). Phía dưới có 1 Button giải và 1 TextView hiển thị kết quả.

<img width="1431" height="776" alt="image" src="https://github.com/user-attachments/assets/0b4de180-dddf-4a0c-bf73-c9798cbb407f" />

# 2. CODE ĐIỀU HƯỚNG (app3activity.java)

Đường dẫn file: app > java > com.example.baitaplonmobile > app3activity.java

<img width="1583" height="922" alt="image" src="https://github.com/user-attachments/assets/28c91468-8633-41e8-a9f0-652e6df95894" />


# SỬ DỤNG MÁY THẬT ANDROID ĐỂ TEST APP 

Bước 1: Bật chế độ nhà phát triển trên đt android 

Bước 2: Bật tính năng gỡ lỗi USB ( cài đặt qua USB ) 

Bước 3: Kết nối điện thoại qua máy tính bằng cáp 

Bước 4: Sau khi cắm sẽ xuất hiện máy thật trên android studio sau đó ấn run để cài đặt app trên điện thoại 

# TEST

APP SAU KHI TẢI THÀNH CÔNG VỀ CÓ TÊN BAITAPLONMOBILE

<img width="720" height="1640" alt="image" src="https://github.com/user-attachments/assets/b24c7e09-4af6-4d28-bdcc-ef7d7cde59c5" />

GIAO DIỆN BAN ĐẦU APP 

<img width="720" height="1640" alt="image" src="https://github.com/user-attachments/assets/a6699be8-62a8-416d-8d77-76496dba5711" />

APP 1: 

<img width="720" height="1640" alt="image" src="https://github.com/user-attachments/assets/abfffb4b-2598-4649-9370-07663dbd778d" />

APP 2: 

<img width="720" height="1640" alt="image" src="https://github.com/user-attachments/assets/a194fd5f-9943-4e27-8b4b-c01027060d7f" />

APP 3: 

<img width="720" height="1640" alt="image" src="https://github.com/user-attachments/assets/ba593b33-8880-497d-8907-5a4c60eea16e" />
