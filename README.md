# Photopea phiên bản mì ăn liền (Offline)

## Why I made this (Tại sao tôi lại tạo thứ này - Tôi: santosguerra)
Người sáng tạo ra [Photopea](https://www.photopea.com/), một công cụ miễn phí thay thế cho Photoshop, không hứng thú với việc tạo ra bản offline của công cụ này, vì vậy tôi đã tự mình tạo ra phiên bản mì ăn liền này.

## Issues (Vấn đề)
Nếu có bất kì vấn đề gì, hãy nói cho tôi biết.

## Requirements (Yêu cầu)
1. Android: Tải và cài đặt [Termux](https://f-droid.org/packages/com.termux/), sau đó cài đặt git và python thông qua app.
1. iOS: Tải và cài đặt [iSH Shell](https://apps.apple.com/us/app/ish-shell/id1436902243), sau đó cài đặt git và python cho hệ điều hành Alpine Linux thông qua app.
1. Windows: Tải và cài đặt [git](https://git-scm.com/downloads) và [python](https://www.python.org/downloads/)
1. Linux: Tải và cài đặt git và python (Câu lệnh cài đặt tùy vào hệ điều hành)

## How to use (Cách sử dụng)
1. Tải Repo này về máy của bạn bằng lệnh `git clone`
1. Mở Terminal 
1. Dùng lệnh `cd` để di chuyển đến nơi mà bạn đã tải code.
1. Ở tại Folder đó, nhập lệnh sau: `python -m http.server --directory www.photopea.com 8080`
1. Mở trình duyệt, truy cập trang [http://localhost:8080](http://localhost:8080). Nó sẽ load và khi hoàn tất, bạn có thể sử dụng bình thường.

## Related Projects (Các project có liên quan)
Lưu ý: Đây không phải là project chính thức của tác giả gốc, project này có liên quan đến các project dưới đây:
* [https://github.com/tim0-12432/photopea](https://github.com/tim0-12432/photopea) -- Công cụ chính tạo nên dự án.
* [https://github.com/NFXT/Photopea-Desktop-App](https://github.com/NFXT/Photopea-Desktop-App) -- 1 công cụ khác góp phần tạo nên dự án.
