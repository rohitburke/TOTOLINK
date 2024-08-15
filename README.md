# TOTOLINK 
Manufacturer's website：https://www.totolink.net/
# Product Information
T10 - Wireless AC1200 Dual Band Smart Mesh Gigabit Router
# Affected Version 
V2_V4.1.8cu.5207
# Download Firmware
https://totolink.com.my/products/t10/

# Vulnerability 
CWE-798: Use of Hard-coded Credentials

# POC
(1) Download the Firmware, extracted those files.

(2) Go to the following path **/squashfs-root/web_cste/cgi-bin/** on your terminal.

(3) Open the product.ini file, by **cat product.ini** you will see the password of telent user.

<img width="582" alt="image" src="https://github.com/user-attachments/assets/f4e34d3a-dc19-4452-b3aa-00bee1951514">



