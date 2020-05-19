---
layout: post
title: No.1 Cài đặt Home Assistant
---

Đây là bài đầu tiên trong chuỗi bài viết hướng dẫn các bạn cài đặt và cấu hình Home Assistant cũng như các thành phần của nó. Hoàn thành chuỗi bài viết này bạn có thể sở hữu một trung tâm tự động hóa cho ngôi nhà của bạn.

## KHUYẾN NGHỊ PHẦN CỨNG
Raspberry là phần cứng phố biến nhất hiện tại và với giá cả phải chăng để làm trung tâm tự động hóa cho căn nhà của bạn. 
> 1. [Raspbery Pi 4 Model B(2GB)](https://www.proe.vn/raspberry-pi-4-model-b-2gram)
> 2. [Bộ nguồn (ít nhất 2A)](https://www.proe.vn/rpi-usb-c-global-power-adapter-5-1v-3a-15-3w)
> 3. [Thẻ nhớ Micro SD](https://www.memoryzone.com.vn/the-nho-microsdhc-sandisk-extreme-v30-a1-667x-32gb-100mbs). Khuyến nghị các bạn sử dụng thẻ A1 32GB hoặc A2 32GB chúng được tối ưu hóa cho các ứng dụng lưu trữ
> 4. [Thiết bị đọc thẻ nhớ](https://www.memoryzone.com.vn/dau-doc-the-transcend-rdf5-chuan-30)
> 5. [Cáp Ethernet](https://www.anphat.vn/san-pham/cable/dintek-patch-cord-utp-cat-5e-5m)

## YÊU CẦU PHẦN MỀM
- Tải về và giải nén vào ổ đĩa của bạn file ảnh Home Assistant dành cho [thiết bị của bạn](https://www.home-assistant.io/hassio/installation/)
- Phần mềm [balenaEtcher](https://www.balena.io/etcher) để ghi file ảnh vào thẻ nhớ.

## TIẾN HÀNH CÀI ĐẶT
1. Cài đặt phần mềm balenaEtcher vào máy tính
2. Cho thẻ nhớ vào đầu đọc thẻ và tién hành kết nối đến máy tính
3. Mở phần mềm balenaEtcher lên và tiến hành flash file ảnh vào thẻ nhớ và chờ cho đến khi quá trình này hoàn tất
4. Gắn thẻ SD vào Raspbery -> Cấp nguồn -> Cắm dây Ethernet vào Raspbery
5. Đợi một lát. Để chắc chắcn quá trình FLASH thành công các bạn hãy chú ý đèn LAN trên Raspberry có nháy không? Nếu có quá trình cài đặt đang diễn ra và có thể đến 20 phút hoặc hơn hãy thưởng thức 1 ly Coca và chờ đợi kết quả.
6. Nếu bạn muốn xem màn hình chờ cài đặt hãy thử truy cập địa chỉ [http://homeassistant.local:8123](http://homeassistant.local:8123) nếu không được hãy thử lại với địa chỉ [http://homeassistant:8123](http://homeassistant:8123). Bạn cũng có thể truy cập bằng địa chỉ IP thông qua đường dẫn có cú pháp sau x.x.x.x:8123 (trong đó x.x.x.x là địa chỉ IP Raspbery trong hệ thống mạng của bạn.)

## KẾT
Đến đây bạn đã sở hữu một trung tâm tự động hóa cho ngôi nhà của bạn. Tuy nhiên để mọi thứ hoạt động với Home Assistant bạn còn phải thực hiện cầu hình rất nhiều. Nào cùng tiếp tục tiến đến bài tiếp theo để có thể cài đặt các dịch vụ của Home Assistant nhé.