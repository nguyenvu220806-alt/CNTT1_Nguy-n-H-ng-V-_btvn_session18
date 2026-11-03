# Phần 1 : Phân tích 
![alt text](image.png)
# Phần 2 : Kiểm thử 
```
.driver-info-box {
    margin-bottom: 20px; /* Đẩy khung dưới ra xa */
}
.station-list-box {
    margin-top: 10px;
    padding: 15px;
}
```
# Phần 3 : Kiểm thử 
- **Nguyên nhân thay đổi margin nhưng phần tử không được di chuyển** : Do có 1 quy tắc CSS khác có độ ưu tiên cao hơn đang ghi đè ở tầng Browser Engine
- **Cách khắc phục và kiểm tra**:
1. Nhìn vào tab Styles trong devtools, tìm xem thuộc tính margin bị gạch bởi dòng nào 
2. Kiểm tra xem có sử dụng từ khóa !important
3. Bỏ chọn các dòng xung đột trực tiếp trên DevTools để xác định chính xác dòng code gây lỗi
