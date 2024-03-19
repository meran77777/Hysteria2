# Hysteria2-Installer


## فارسی

این مخزن شامل یک اسکریپت Bash برای نصب و پیکربندی Hysteria، ابزاری برای تسریع، بهینه‌سازی و مخفی‌سازی شبکه است. این اسکریپت فرایند راه‌اندازی Hysteria روی سرور شما را ساده می‌کند.

### ویژگی‌های اسکریپت

- **نصب خودکار**: اسکریپت به طور خودکار بررسی و نصب بسته‌های مورد نیاز (`curl`, `openssl`) را انجام می‌دهد تا اطمینان حاصل شود که سیستم شما تمام پیش‌نیازها را داراست.
- **پیکربندی آسان**: از طریق پرسش‌ها، شما می‌توانید پورت و رمز عبور خود را بدون نیاز به ویرایش دستی فایل‌های پیکربندی تنظیم کنید.
- **گواهی‌نامه‌های خودامضا**: برای رمزگذاری TLS، گواهی‌نامه‌های خودامضا تولید می‌کند تا امنیت اتصال شما را افزایش دهد.
- **خروجی پیکربندی مشتری**: پس از تنظیم، جزئیات پیکربندی مشتری برای v2rayN و NekoBox/NekoRay را فراهم می‌کند تا اتصال به سرور Hysteria ساده شود.

### استفاده

1. **دانلود اسکریپت**: این مخزن را کلون کنید یا اسکریپت را مستقیماً دانلود کنید.
2. **اجرای اسکریپت**: اسکریپت را با `chmod +x hysteria2-installer.sh` قابل اجرا کنید و آن را با استفاده از `./hysteria2-installer.sh` اجرا کنید.
3. **پاسخ به پرسش‌ها**: هنگامی که پرسیده شد، پورت و رمز عبور مورد نظر خود را وارد کنید.
4. **اتصال**: برای اتصال به سرور Hysteria خود، از جزئیات پیکربندی مشتری ارائه‌شده استفاده کنید.


## English

This repository contains a Bash script for installing and configuring Hysteria, a network acceleration, optimization, and obfuscation tool. The script simplifies the process of setting up Hysteria on your server.
    Note: This script is intended for use on a Linux-based server.

### Script Features

- **Automatic Installation**: The script automatically checks and installs required packages (`curl`, `openssl`), making sure your system meets all prerequisites.
- **Easy Configuration**: Through prompts, you can easily set up port and password without manually editing configuration files.
- **Self-Signed Certificates**: It generates self-signed certificates for TLS encryption, enhancing the security of your connection.
- **Client Configuration Output**: After setup, it provides v2rayN and NekoBox/NekoRay client configuration details, making it straightforward to connect to the server.

### Usage

1. **Download the Script**: Clone this repository or download the script directly.
2. **Run the Script**: Make the script executable with `chmod +x hysteria2-installer.sh` and run it using `./hysteria2-installer.sh`.
3. **Follow Prompts**: Enter your preferred port and password when prompted.
4. **Connect**: Use the provided client configuration details to connect to your Hysteria server.
