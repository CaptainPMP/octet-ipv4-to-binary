# Octet — IPv4 Workbench

**English | [ภาษาไทย](#ภาษาไทย)**

---

## English

### What is Octet?

Octet is a small web page that helps you learn IPv4 addresses. It is one single HTML file. You can open it in any modern browser. You do not need to install anything.

### Features

1. **Address converter**
   - Change an IPv4 address from decimal to binary (example: `192.168.1.1`).
   - Change an IPv4 address from binary to decimal.
   - Click any bit (0 or 1) to flip it and see the number change.
   - Also shows hexadecimal and the integer value.

2. **Subnet calculator**
   - Type an address with a prefix (`192.168.1.10/24`) or with a mask (`192.168.1.10 255.255.255.0`).
   - See the network address, broadcast address, first and last host, number of hosts, wildcard mask, class and address type.
   - See which bits belong to the network and which belong to the host.
   - Split a network into smaller subnets (shows up to the first 64).

3. **Reference sheet**
   - Prefix lengths, masks and usable hosts.
   - Special ranges (private, loopback, multicast, and more).
   - Common ports (SSH, DNS, HTTP, HTTPS, and more).

4. **Practice**
   - Short drill: convert one octet between decimal and binary.
   - Keeps your score.

### How to use

1. Download the file `Octet — IPv4 workbench.html`.
2. Double-click it to open it in your browser.
3. Use the menu at the top: Converter, Subnets, Reference, Practice.

Tip: In the practice section, press **Enter** to check your answer and press **Enter** again for the next question.

### Quick lesson

An IPv4 address has 4 numbers. Each number is called an **octet**. One octet has 8 bits. So the full address has 32 bits.

Bit weights from left to right are:

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|-----|----|----|----|---|---|---|---|

Example: `192` = 128 + 64 = `11000000`

### Notes

- Everything runs in your browser. Nothing is sent or saved.
- The page loads the Playfair Display font and Tailwind CSS from the internet. If you are offline, the page still works, but it may look different.
- Dark mode works automatically with your device setting.

### Built with

- HTML, CSS and plain JavaScript
- Tailwind CSS (from CDN)
- Google Fonts (Playfair Display)

---

## ภาษาไทย

### Octet คืออะไร?

Octet เป็นหน้าเว็บเล็ก ๆ ที่ช่วยให้คุณเรียนรู้เรื่อง IPv4 address เป็นไฟล์ HTML ไฟล์เดียว เปิดได้ในเบราว์เซอร์ทั่วไป ไม่ต้องติดตั้งอะไรเพิ่ม

### ฟีเจอร์

1. **ตัวแปลง address**
   - แปลง IPv4 จากเลขฐานสิบเป็นเลขฐานสอง (เช่น `192.168.1.1`)
   - แปลง IPv4 จากเลขฐานสองเป็นเลขฐานสิบ
   - กดที่บิต (0 หรือ 1) เพื่อสลับค่า แล้วดูตัวเลขเปลี่ยนไป
   - แสดงค่าฐานสิบหกและค่าเลขจำนวนเต็มด้วย

2. **เครื่องคำนวณ subnet**
   - พิมพ์ address พร้อม prefix (`192.168.1.10/24`) หรือพร้อม mask (`192.168.1.10 255.255.255.0`)
   - ดู network address, broadcast address, host ตัวแรกและตัวสุดท้าย, จำนวน host, wildcard mask, class และประเภทของ address
   - ดูว่าบิตไหนเป็นของ network และบิตไหนเป็นของ host
   - แบ่ง network เป็น subnet ย่อย (แสดงสูงสุด 64 อันแรก)

3. **ตารางอ้างอิง**
   - ความยาว prefix, mask และจำนวน host ที่ใช้ได้
   - ช่วง address พิเศษ (private, loopback, multicast และอื่น ๆ)
   - พอร์ตที่พบบ่อย (SSH, DNS, HTTP, HTTPS และอื่น ๆ)

4. **ฝึกทำโจทย์**
   - แบบฝึกสั้น ๆ: แปลง octet หนึ่งตัวระหว่างเลขฐานสิบกับฐานสอง
   - เก็บคะแนนให้

### วิธีใช้

1. ดาวน์โหลดไฟล์ `Octet — IPv4 workbench.html`
2. ดับเบิลคลิกเพื่อเปิดในเบราว์เซอร์
3. ใช้เมนูด้านบน: Converter, Subnets, Reference, Practice

เคล็ดลับ: ในส่วน Practice กด **Enter** เพื่อตรวจคำตอบ และกด **Enter** อีกครั้งเพื่อไปข้อต่อไป

### บทเรียนสั้น ๆ

IPv4 address มีตัวเลข 4 ตัว แต่ละตัวเรียกว่า **octet** หนึ่ง octet มี 8 บิต ดังนั้น address เต็มมี 32 บิต

น้ำหนักของบิต จากซ้ายไปขวา คือ:

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|-----|----|----|----|---|---|---|---|

ตัวอย่าง: `192` = 128 + 64 = `11000000`

### หมายเหตุ

- ทุกอย่างทำงานในเบราว์เซอร์ของคุณ ไม่มีการส่งหรือบันทึกข้อมูลใด ๆ
- หน้าเว็บโหลดฟอนต์ Playfair Display และ Tailwind CSS จากอินเทอร์เน็ต ถ้าไม่มีอินเทอร์เน็ต หน้าเว็บยังใช้งานได้ แต่หน้าตาอาจต่างไป
- Dark mode ทำงานอัตโนมัติตามการตั้งค่าของอุปกรณ์

### สร้างด้วย

- HTML, CSS และ JavaScript ธรรมดา
- Tailwind CSS (จาก CDN)
- Google Fonts (Playfair Display)
