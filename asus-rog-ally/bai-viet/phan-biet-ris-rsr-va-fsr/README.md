# Phân biệt giữa các công nghệ xử lý hình ảnh của AMD là RIS, RSR và FSR trong Rog Ally (07/09/2023)

## Mở đầu

- Các bạn đang sử dụng Rog Ally hoặc các handheld PC sử dụng APU AMD thì có lẽ đã thường xuyên gặp các lựa chọn tối ưu đồ hoạ từ công nghệ của AMD như RIS, RSR và FSR, nhưng lại không biết các công nghệ này có tác dụng gì thì mình tình cờ tìm thấy một bài viết không quá đi sâu về kỹ thuật nhưng đủ để người dùng cuối như chúng ta có cái nhìn tổng quan về các công nghệ này https://allyguide.com/software/ris-rsr-and-fsr-whats-the-difference/ 

## Tóm gọn ý từ bài viết

- `RIS` (Radeon Image Sharpening) được cài đặt ở mức driver, tức là áp dụng cho tất cả các game, cơ chế là sẽ dùng thuật toán AI để làm cho các hình ảnh độ phân giải thấp khi scale lên cao sẽ được làm "thon gọn" các cạnh để trông nuột hơn. Có thể hiểu nó giống "anti aliasing"
  - RIS là giải pháp ít ảnh hưởng hiệu năng nhất
  - Tìm hiểu thêm: https://www.amd.com/en/technologies/radeon-image-sharpening

- `FSR` (FidelityFX Super Resolution) chỉ có thể cài đặt trên từng game có hỗ trợ, sử dụng thuật toán AI để upscale hình ảnh lên độ phân giải mong muốn (giả sử độ phân giải game là 720p, nhưng màn hình 1080p nó sẽ giúp scale cái 720p -> 1080p), đây được xem là giải pháp upscale tốt nhất hiện nay của AMD
  - Tìm hiểu thêm: https://www.amd.com/en/technologies/radeon-super-resolution 

- `RSR` (Radeon Super Resolution) tương tự FSR nhưng áp dụng được cho tất cả các game, hiệu quả không ngon bằng FSR vì có thể gây ra hiệu ứng "blur"
  - Có nên bật cả RSR và FSR không? -> câu trả lời từ AMD là không nên, trong một số tình huống nó có thể làm hình ảnh bị xấu đi
  - Tìm hiểu thêm: https://www.amd.com/en/technologies/radeon-super-resolution

- **Tổng kết:** nếu phải lựa chọn thì thứ tự ưu tiên sẽ là FSR > RSR > RIS (bên trái là ưu tiên hơn)

## Quan điểm cá nhân

- Bài viết trên có thể có nhiều chi tiết chưa đúng hoàn toàn, nhưng với mình nó cung cấp đủ thông tin để chúng ta hiểu là nên dùng gì và nó có công dụng ra sao. Ngoài ra chúng ta cũng không cần quá chi ly, chỉ nên nhìn trên kết quả mà nó đạt được khi sử dụng. Nếu có thông tin nào chưa đúng và bị sai lệch nhiều rất mong nhận được sự góp ý từ mọi người ^^ !

- Hãy thử từng lựa chọn tối ưu trên khi chơi game, lựa chọn nào bạn cảm thấy tối ưu nhất thì nó là tốt nhất dành cho bạn. Cá nhân mình đang sử dụng phương án sử dụng RIS kết hợp độ phân giải 900p trên Rog Ally, mang lại chất lượng hình ảnh và hiệu năng rất tốt (nhiều user trên reddit cũng recommend sử dụng phương án này)

