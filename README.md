1. So sánh Đường dẫn Tuyệt đối và Tương đối

Đường dẫn Tuyệt đối (Absolute Path):
 Nó là gì: Địa chỉ gắn cố định từ ổ đĩa gốc (Ví dụ: C:\Users\Ban_Than\Desktop\...).
 
Hạn chế: Đổi sang máy tính khác là bị lỗi gãy đường dẫn ngay lập tức vì khác tên người dùng/ổ đĩa.

Đường dẫn Tương đối (Relative Path):
 Nó là gì: Địa chỉ tính từ vị trí của file code đang chạy (Dùng dấu . hoặc ..).
 
Ưu điểm: Cực kỳ linh hoạt, mang sang bất kỳ máy nào cũng chạy được mà không sợ lỗi.


2. Tính thời gian tải file 2GB với mạng 80 Mbps
Quy tắc đổi đơn vị (Bẫy Bit và Byte): 1 byte = 8 bit

THỜI GIAN HOÀN THÀNH LÀ 80MPS = 10MB , 2GB = 2048 MB .SUY RA 2048 : 10 = 204.8 GIÂY


PHẦN 2: HÀNH ĐỘNG KỸ THUẬT

1. Viết lại đường dẫn tương đối (Relative Path)

Nếu file code nằm ngay trong thư mục Project: './data/db.csv'

Nếu file code nằm trong thư mục con src/ (cần lùi ra 1 cấp để vào data): '../data/db.csv'


2. Các bước bật "View Options" để nhận diện mã độc

Bước 1: Mở thư mục chứa file trong File Explorer.

Bước 2: Bấm vào thẻ View ở thanh công cụ phía trên cùng.

Bước 3: Tích chọn vào ô File name extensions (Hiển thị phần mở rộng của tên file).

👉 Kết quả: File giả mạo sẽ lộ rõ đuôi thật là tai-lieu-on-tap.pdf.exe (file thực thi nguy hiểm), giúp bạn biết để xóa ngay lập tức, không bấm mở.
