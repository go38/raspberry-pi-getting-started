## Một vòng khám phá Raspberry Pi

Bây giờ là lúc để khám phá Pi Raspberry.

+ Thấy biểu tượng Quả mân xôi (Raspberry) ở góc trên bên trái chứ? Đó là nơi bạn truy cập vào menu: nhấp vào nó và bạn sẽ tìm thấy rất nhiều ứng dụng.

+ Nhấp vào **Accessories** và chọn **Text Editor**.

![ảnh chụp màn hình](images/pi-accessories.png)

+ Nhập `I just built a Raspberry Pi` trong cửa sổ xuất hiện.

![ảnh chụp màn hình](images/pi-text-editor.png)

+ Nhấp vào **File**, sau đó chọn **Save**, rồi nhấp vào **Desktop** và lưu tệp dưới tên `rp.txt`.

![ảnh chụp màn hình](images/pi-save.png)

+ Bạn sẽ thấy một biểu tượng có tên `rp.txt` xuất hiện trên màn hình nền.

![ảnh chụp màn hình](images/pi-saved.png)

Tệp của bạn đã được lưu vào thẻ SD của Raspberry Pi.

+ Đóng trình chỉnh sửa văn bản bằng cách nhấp vào **X** ở góc trên cùng bên phải của cửa sổ.

+ Quay lại menu Raspberry, chọn **Shutdown**, sau đó chọn **Reboot** để khởi động lại.

+ Khi Pi đã khởi động lại, tệp của bạn sẽ vẫn ở đó.

+ Raspberry Pi chạy một phiên bản của một hệ điều hành được gọi là Linux (Windows và MacOS là các hệ điều hành khác). Nó cho phép bạn thực hiện mọi thứ bằng cách gõ lệnh thay vì nhấp vào các tùy chọn menu. Nhấp vào **Terminal** ở trên cùng màn hình:

![ảnh chụp màn hình](images/pi-command-prompt.png)

+ Trong cửa sổ xuất hiện, gõ:

    ls
    

và sau đó nhấn <kbd>Enter</kbd> trên bàn phím.

Thao tác này sẽ liệt kê các tệp trong thư mục `home` của bạn.

+ Bây giờ gõ lệnh này để **c**hange **d**irectory (điều hướng) vào Desktop:

    cd Desktop
    

Bạn phải nhấn phím <kbd>Enter</kbd> sau mỗi lệnh.

Gõ:

    ls
    

Bạn có thấy tệp tin bạn đã tạo không?

+ Đóng cửa sổ Terminal bằng cách nhấp vào **X**.

+ Bây giờ kéo `rp.txt` vào Wastebasket trên màn hình nền để Pi sẵn sàng cho người tiếp theo.
    
    ![ảnh chụp màn hình](images/pi-waste.png)