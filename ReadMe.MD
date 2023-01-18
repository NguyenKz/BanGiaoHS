# Mở đầu 
## Giới thiệu
+ Mình viết biên bản bàn giao automation. Mình không giải thích lại toàn bộ code automation mà chỉ có thể giới thiệu một số công nghệ và hướng tiếp cận để các bạn có thể tự handle lại hoặc viết mới phần automation của mình.
## Công nghệ:
+ 0: XPATH:
    * Giới thiệu: Xpath là một địa chỉ của một hay nhiều tags, elements trong html. Có thể tham khảo chi tiết tại đây "https://www.guru99.com/xpath-selenium.html"
+ 1: Selenium:
    * Giới thiệu: Đây là công nghệ dùng cho automation testing, chúng ta có thể sử dụng công nghệ này để thực hiện các thao tác của người dùng lên trình duyệt web. Các bạn có thể tìm hiểu thêm trên google.
+ 2: Requests:
    * Đây là 1 thư viện của python, nó cũng khá giống với selenium nhưng chúng ta không thể render javascript và cũng không thể  hoặc khó khăn trong việc thực hiện các thao tác của người dùng như click 1 button, gõ text vào textbox.
## Selenium
+ 1: Cài đặt:
    * Selenium cần phải có 1 webbrowser driver tương thích với phiên bản của <b>webbrowser</b>, ví dụ như chrome hay firefox. Sau đây mình sẽ tiến hành cài đặt và mở thử 1 trang web với selenium chrome.
+ 2: Demo:
    * Mình demo đăng nhập vào Facebook bằng selenium trên jupyter notebook demo_01.ipynb
    * Mình sẽ demo thực hiện tác vụ thích ngẫu nhiên các bài viết trên new feeds trên jupyter notebook demo_02.ipynb
    * Mình sẽ demo thực hiện tác vụ gửi tin nhắn trên jupyter notebook demo_03.ipynb
    
### Video:
+ 1: 