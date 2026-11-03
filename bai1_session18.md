# Phần 1 : Phân tích 
- Input : phong-dieu-phoi.greenlog.vn
- Output : Địa chỉ máy chủ 
- Sơ đồ luồng : Trình duyệt -> ISP (nhà mạng) -> Root name sever -> TLD sever 
# Phần 2 : Triển khai
 **DNS_PROBE_FINISHED_NXDOMAIN** : lỗi ở phía client/mạng

 **500 Internal Server Error** : lỗi ở phía sever 

 **Kiểm tra Status code** :  Nhấn F12 -> Chọn tab netwwork -> tải lại trang (F5)
 # Phần 3 : Kiểm thử 
 - Ràng buộc : Gõ nhầm tên miền (grenlog.vn)
 - Mã 404 not found : tài nguyên trang không tồn tại 
