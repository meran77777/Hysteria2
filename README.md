# Hysteria2-Installer


## فارسی

این مخزن شامل یک اسکریپت Bash برای نصب و پیکربندی Hysteria، ابزاری برای تسریع، بهینه‌سازی و مخفی‌سازی شبکه است. این اسکریپت فرایند راه‌اندازی Hysteria روی سرور شما را ساده می‌کند.

### ویژگی‌های اسکریپت

- **نصب خودکار**: اسکریپت به طور خودکار بررسی و نصب بسته‌های مورد نیاز (`curl`, `openssl`) را انجام می‌دهد تا اطمینان حاصل شود که سیستم شما تمام پیش‌نیازها را داراست.
- **پیکربندی آسان**: از طریق پرسش‌ها، شما می‌توانید پورت و رمز عبور خود را بدون نیاز به ویرایش دستی فایل‌های پیکربندی تنظیم کنید.
- **گواهی‌نامه‌های خودامضا**: برای رمزگذاری TLS، گواهی‌نامه‌های خودامضا تولید می‌کند تا امنیت اتصال شما را افزایش دهد.
- **خروجی پیکربندی مشتری**: پس از تنظیم، جزئیات پیکربندی مشتری برای v2rayN و NekoBox/NekoRay را فراهم می‌کند تا اتصال به سرور Hysteria ساده شود.

### استفاده

bash <(curl -Ls https://github.com/meran77777/Hysteria2/releases/download/v1/hysteria.sh)


## English

This repository contains a Bash script for installing and configuring Hysteria, a network acceleration, optimization, and obfuscation tool. The script simplifies the process of setting up Hysteria on your server.
    Note: This script is intended for use on a Linux-based server.

### Script Features

- **Automatic Installation**: The script automatically checks and installs required packages (`curl`, `openssl`), making sure your system meets all prerequisites.
- **Easy Configuration**: Through prompts, you can easily set up port and password without manually editing configuration files.
- **Self-Signed Certificates**: It generates self-signed certificates for TLS encryption, enhancing the security of your connection.
- **Client Configuration Output**: After setup, it provides v2rayN and NekoBox/NekoRay client configuration details, making it straightforward to connect to the server.

### Usage

bash <(curl -Ls https://github.com/meran77777/Hysteria2/releases/download/v1/hysteria.sh)

