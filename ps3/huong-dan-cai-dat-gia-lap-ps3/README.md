# Hướng dẫn cài đặt giả lập PS3 bằng phần mềm RPCS3 trên Rog Ally

## Mở đầu

- Sau rất rất nhiều năm kể từ khi PS3 ra mắt thì cho đến thời điểm hiện tại, giả lập PS3 vẫn là một cái gì đó rất khoai, trong các team làm giả lập thì trụ đến giờ và làm tốt nhất có lẽ là team làm RPCS3. Tuy thời gian phát triển của RPCS3 đã rất lâu nhưng nếu so với giả lập của PS2 hoặc các hệ máy cũ hơn thì RPCS3 vẫn rất thiếu ổn định trong rất nhiều tựa game, vẫn còn rất nhiều game để có thể chơi được trên RPCS3 ta phải tiến hành custom một số config cho riêng từng game (may mắn là RPCS3 có hỗ trợ cusom config cho riêng từng hệ game và lưu lại config đó). 

- Tốt nhất trước khi xác định bỏ công sức ra cài đặt giả lập PS3 thì bạn nên thử tìm hiểu trước game của bạn trên youtube xem đã có ai giả lập thành công chưa và xem feedback từ phía các gamer xem có vấn đề gì không rồi hãy quyết định có nên tiếp tục cài đặt giả lập RPCS3 hay không.
  - RPCS3 có một trang thống kê các game PS3 đã được họ test là chơi được hay chưa, bạn có thể tìm kiếm trước tại đây: https://rpcs3.net/compatibility 
  - Yên tâm là đã có rất nhiều tựa game nổi tiếng có thể chơi ngon lành trên RPCS3 rồi: God of war 3, persona, redeem redemption,...

- Hướng dẫn của mình cũng chỉ dựa trên hướng dẫn gốc của RPCS3 tại trang: https://rpcs3.net/quickstart và một số video trên youtube. Nếu gặp khó khăn với hướng dẫn bên dưới bạn nên tìm trên youtube để dễ hình dung hơn.

## Hướng dẫn

### Bước 1: 

Tải RPCS3 mới nhất tại https://rpcs3.net/download . Tìm ô biểu tượng windows và bấm vào `Download` để tải file mới nhất

![](./ps3-01.jpg)

### Bước 2: 

Sau khi tải file xong ta sẽ được 1 file `.7z` với cái tên kiểu như `rpcs3-v0.0.28-15391-782344ee_win64.7z`. Tiến hành giải nén file này vào môt thư mục
  - Cái tên file sẽ cho ta biết version của nó là `v0.0.28-15391-782344ee` và phiên bản là windows 64 bit -> sau này nếu có báo lỗi thì bạn nên lưu ý phần version này
  - Để giải nén được file `.7z` thì bạn vui lòng cài phần mềm 7-zip tại https://www.7-zip.org/download.html 

![](./ps3-02.jpg)

### Bước 3: 

Vào thư mục đã giải nén mở file `rpcs3`

![](./ps3-03.jpg)

### Bước 4: 

Khi mở file `rpcs3` lên ta sẽ được cửa sổ như hình dưới. Làm các bước:
  1. Check vào (1) nếu bạn không muốn cái popup này hiển thị lần nữa
  2. Check vào (2) để đảm bảo bạn đã đọc hướng dẫn sử dụng trước khi dùng để nó cho phép bạn bấm tiếp vào (3)
  3. Sau khi check vào (2) thì bấm vào (3)

![](./ps3-04.jpg)

### Bước 5: 

Sau bước 4 thì nó sẽ hiển thị cửa sổ app RPCS3, trước khi làm tiếp thì ta phải tiếng hành tải firmware của PS3. Bạn vào trang https://www.playstation.com/en-us/support/hardware/ps3/system-software/ -> tìm dòng `Update using a computer` bấm vào để nó hiển thị được cái nút `Download PS3 Update` -> tải file về máy là xong bước này.
  - Thường firmware của PS3 sẽ là file có tên `PS3UPDAT.PUP`
  
![](./ps3-05.jpg)

### Bước 6: 

Sau khi đã có file firmware ta phải tiến hành import nó vào RPCS3