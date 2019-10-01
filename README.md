# cngDocs
Hướng dẫn thiết lập mạch chuyển nguồn và hệ thống hass

## Mục lục
[1. Các thông tin được thiết lập mặc định](#cac-thong-tin-duoc-thiet-lap-mac-dinh)

[2. Thiết lập wifi cho HASS](#thiết-lập-wifi-cho-hệ-thống-hass)

[3. Cài đặt python và ESPHome](#cài-đặt-python-và-ESPHome)

[4. Thiết lập wifi cho ESP32](#thiết-lập-wifi-cho-esp32)

[5. Thêm thông tin mạch chuyển nguồn trên HASS](#thêm-thông-tin-mạch-chuyển-nguồn-trên-hass)

## Các thông tin được thiết lập mặc định
[Quay về mục lục](#mục-lục)

wifi mặc định trên mạch chuyển nguồn và hass

```
  Tên wifi (ssid): "Pyralink Lab"
  Mật khẩu (password/psk): "20171025"
```

Tài khoản admin hệ thống hass

```
  user: "yasuo"
  password: "tamdat0801"
```

Tài khoản kết nối vào raspberry 

```
  user: "pi"
  password: "tamdat0801"
```

Đỉa chỉ giao diện web của hệ thống hass (phải kết nối chung mạng)

```icar.local:8123``` hoặc ```icar.local:8124```

## Thiết lập wifi cho hệ thống hass
[Quay về mục lục](#mục-lục)

### Bước 1
- Phát wifi mặc định với tên wifi và mật khẩu (có thể dùng chức năng phát wifi trên điện thoại có hỗ trợ).

```
  Tên wifi (SSID): “Pyralink Lab”
  Mật khẩu (PSK): “20171025”
```

-	Khởi động thiết bị và chờ đèn báo thiết bị đã sẵn sàng.
-	Kết nối Laptop chung với wifi mặc định mà thiết bị đang kết nối đến.
-	Có thể mở cmd và ping kiểm tra thiết bị đã được kết nối hay chưa.
- Nhập lệnh ```ping icar.local``` và enter
-	Kết quả nếu thiết bị đã kết nối là địa chỉ IP của thiết bị (IP V4 hoặc V6)

## Cài đặt python và ESPHome
[Quay về mục lục](#mục-lục)


## Thiết lập wifi cho ESP32
[Quay về mục lục](#mục-lục)


## Thêm thông tin mạch chuyển nguồn trên HASS
[Quay về mục lục](#mục-lục)


