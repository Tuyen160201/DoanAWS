
#### Bước 1. Truy cập dịch vụ AWS CloudFormation bằng 3 cách:
- Chọn **CloudFormation** từ trong **Management Tools**.
- Tìm kiếm CloudFormation bằng thanh tìm kiếm.
- Chọn **CloudFormation** từ **Recently visited services** nếu bạn đã sử dụng CloudFormation gần đây.
#### Bước 2. Tạo Template cho Stack.
Trên trang Specify template, chọn 1 stack template bằng cách sử dụng một trong các tùy chọn sau:
- **Template is ready**.

  Chỉ định một mẫu đã hoàn thành mà bạn đã sẵn sàng để tạo ngăn xếp.

  Trong phần **Specify template**, hãy chọn tùy chọn thích hợp dựa trên vị trí của mẫu:
  - **URL Amazon S3**

    Chỉ định URL cho một mẫu trong nhóm S3.

    Nhập URL vào trường URL **Amazon S3**.
    
  - **Upload a template file**
  
    Chọn mẫu CloudFormation trên máy tính local của bạn.
    
    Chọn **Choose File** để chọn tệp mẫu mà bạn muốn tải lên. Khi bạn đã chọn mẫu của mình, CloudFormation tải tệp lên và hiển thị URL S3.

- **Sử dụng sample template**.

  Chọn một mẫu mẫu từ bộ sưu tập các mẫu do CloudFormation cung cấp để giúp bạn bắt đầu. Để biết mô tả về các mẫu, hãy xem **Sample templates**.

  Để xem thêm các mẫu và đoạn mã mẫu, được tổ chức bởi dịch vụ AWS, hãy nhấp vào **View more sample templates**.

- **Tạo template trên Designer**.
  
  Tạo hoặc sửa đổi mẫu bằng AWS CloudFormation Designer, một giao diện kéo và thả để lập sơ đồ đồ họa các mẫu của bạn.
  
Để chấp nhận cài đặt của bạn, hãy chọn **Next** và tiếp tục **chỉ định tên ngăn xếp và các thông số**.
  - Trên trang **Specify stack details**, hãy nhập tên ngăn xếp vào **Stack name**.


  - Trong phần **Parameters**, chỉ định các tham số được xác định trong mẫu ngăn xếp.


  - Khi bạn hài lòng với các giá trị tham số, hãy chọn **Next** để tiếp tục thiết lập các tùy chọn cho ngăn xếp của bạn.

Xem xét và tạo Stack:

- Trên trang **Review**, hãy xem lại chi tiết về Stack của bạn. Nếu bạn cần thay đổi bất kỳ giá trị nào trước khi khởi chạy ngăn xếp, hãy chọn **Edit** trên phần thích hợp để quay lại trang có cài đặt mà bạn muốn thay đổi.

- Sau khi bạn xem lại cài đặt tạo ngăn xếp và chi phí ước tính của ngăn xếp, hãy chọn **Create stack** để khởi chạy ngăn xếp của bạn.
  
