---
title: reverse engineering

---

> reverse engineering

1. Hiểu nền tảng cơ bản
- Ngôn ngữ lập trình: Thành thạo C/C++ và hiểu chút về Assembly (x86, x64) là rất cần thiết.
- Kiến thức hệ điều hành: Biết cách hoạt động của memory, stack, heap, và các cơ chế bảo vệ như ASLR, NX, DEP.
- Công cụ: Làm quen với các tool phổ biến:
IDA Pro / Ghidra: Phân tích mã nhị phân.
x64dbg / OllyDbg: Debug runtime.
 Radare2: Tool mở rộng, nhẹ nhưng mạnh mẽ.
Binwalk / strings / objdump: Tool phân tích sơ bộ.
2. Học qua bài tập cơ bản
- CTF challenges cơ bản: Làm thử các bài từ các nền tảng như pwnable.kr, CTFlearn, hoặc OverTheWire.
- Crackme: Tìm các bài CrackMe trên Crackmes.one, phân tích keygen hoặc bypass password.
3. Thực hành nâng cao
- Tăng level với các bài CTF:
Thử sức ở các giải CTF như picoCTF, Hack The Box, hoặc CTFtime.
Đọc write-up của người khác để học cách giải bài.
- Phá bảo vệ (anti-debugging):
Làm quen với các kỹ thuật chống debug như packer, obfuscation, và bypass chúng.
- Khám phá malware analysis:
Nâng cao kỹ năng bằng cách tìm hiểu static và dynamic analysis.
4. Tìm mentor hoặc cộng đồng
- Tham gia các cộng đồng như:
CTF Việt Nam trên Facebook/Discord.
- Theo dõi các streamer làm reverse hoặc blog như LiveOverflow.
5. Duy trì thói quen và mindset
- Hãy nhớ: Kiên nhẫn, không sợ sai, và chịu khó học hỏi. Reverse không phải thứ học trong ngày một ngày hai, nhưng mỗi bước cậu đi đều giá trị.


> học reverse sau này làm gì???

1. Security Researcher (Nhà nghiên cứu bảo mật)
- Ứng dụng từ CTF:
Phân tích lỗ hổng phần mềm (bug hunting, vulnerability research).
Khai thác các lỗi bảo mật (exploit development).
- Thực tế:
Làm việc với các công ty bảo mật hoặc nhóm nghiên cứu như Google Project Zero.
Tìm và báo cáo lỗi để nhận bounty (bug bounty programs).
2. Malware Analyst (Phân tích mã độc)
- Ứng dụng từ CTF:
Phân tích mã nhị phân của malware, bypass các cơ chế chống phân tích.
Reverse các hành vi của ransomware, spyware.
- Thực tế:
Bảo vệ hệ thống của doanh nghiệp khỏi mã độc.
Cung cấp giải pháp phục hồi sau tấn công.
3. Reverse Engineer (Chuyên gia dịch ngược)
- Ứng dụng từ CTF:
Phân tích cách hoạt động của phần mềm, firmware, hoặc các file hệ thống.
Bypass cơ chế bảo vệ hoặc tối ưu phần mềm.
- Thực tế:
Làm việc trong ngành công nghiệp phần mềm hoặc bảo mật.
Tạo ra các bản vá (patch) hoặc phát triển công cụ bảo mật.
4. Penetration Tester / Red Team
- Ứng dụng từ CTF:
Khai thác lỗ hổng trong ứng dụng, mạng, và hệ thống.
Tìm hiểu cách tấn công và phòng thủ hệ thống thực tế.
- Thực tế:
Kiểm thử bảo mật cho các công ty, giúp họ cải thiện hệ thống.
5. Game Security hoặc Software Development
- Ứng dụng từ CTF:
Phát hiện và ngăn chặn hack trong game (anti-cheat systems).
Làm các tool phát triển phần mềm liên quan đến bảo mật.
- Thực tế:
Làm việc tại các studio game hoặc công ty phần mềm.
6. Cyber Threat Intelligence
- Ứng dụng từ CTF:
Phân tích chiến thuật, kỹ thuật của hacker.
Tìm hiểu các cuộc tấn công mục tiêu.
- Thực tế:
Dự đoán và bảo vệ trước các cuộc tấn công tiềm năng.
7. Giá trị mềm
- Tư duy logic và giải quyết vấn đề: CTF dạy cậu cách phân tích vấn đề phức tạp và tìm giải pháp sáng tạo.
- Kỹ năng học tập độc lập: Khả năng tự tìm kiếm thông tin, học hỏi từ tài liệu, và áp dụng thực tế.
- Tính kiên nhẫn và sự tò mò: Hai yếu tố cực kỳ quan trọng trong bất kỳ ngành nghề nào.
> lộ trình CTF

1. Cơ bản về lập trình và cấu trúc dữ liệu
Ngôn ngữ lập trình: Học ít nhất một ngôn ngữ lập trình như C/C++ (quan trọng trong reverse engineering) và Python (dễ dàng cho scripting và automation).
Cấu trúc dữ liệu và giải thuật: Đây là nền tảng để giải quyết các bài toán trong CTF, giúp bạn hiểu cách tổ chức và xử lý dữ liệu.
2. Kiến thức về hệ điều hành và mạng
Hệ điều hành: Học về hệ điều hành (Windows và Linux) vì bạn sẽ cần kiến thức về cách hệ điều hành quản lý bộ nhớ, quy trình, và các API. Cũng cần biết sử dụng công cụ như gdb, strace, ltrace.
Mạng: Cần hiểu TCP/IP, DNS, HTTP, và các giao thức mạng khác để giải quyết các bài về web và bảo mật mạng trong CTF.
3. Bảo mật thông tin cơ bản
Mã hóa và giải mã: Hiểu các thuật toán mã hóa cơ bản như XOR, Base64, AES, RSA.
Tấn công và phòng ngự: Học các tấn công cơ bản như buffer overflow, format string, SQL injection.
4. Reverse Engineering
Phần mềm và công cụ reverse:
IDA Pro, Ghidra, Radare2: Các công cụ phân tích mã nguồn máy tính và ngược lại.
OllyDbg, x64dbg: Các debugger dùng để phân tích chương trình.
Binary Ninja: Công cụ phân tích nhị phân.
Tìm hiểu về Assembly: Ngôn ngữ máy là cần thiết khi bạn làm việc với mã nguồn đã được biên dịch, vì phần lớn các bài CTF reverse sẽ yêu cầu bạn phân tích và hiểu các chương trình dưới dạng Assembly.
Quản lý bộ nhớ: Học về stack, heap, và cách quản lý bộ nhớ của chương trình để hiểu được cách khai thác các lỗi bảo mật.
5. Thực hành với các bài CTF
TryHackMe: Đây là một nền tảng tuyệt vời cho các bài học về bảo mật và reverse.
Hack The Box: Cung cấp nhiều phòng thử nghiệm về các kỹ năng bảo mật khác nhau, trong đó có reverse engineering.
OverTheWire: Có các bài tập CTF cơ bản về các kỹ thuật bảo mật, bao gồm reverse engineering.
Root Me: Cung cấp nhiều challenges về reverse engineering và bảo mật khác.
6. Đọc sách và tài liệu chuyên sâu
Practical Reverse Engineering: Cung cấp những kiến thức cơ bản và nâng cao về reverse engineering.
The Art of Software Security Assessment: Một tài liệu tuyệt vời về bảo mật phần mềm và phân tích mã độc.
Hacking: The Art of Exploitation của Jon Erickson: Giới thiệu các kỹ thuật tấn công và khai thác lỗi bảo mật, rất phù hợp với các bài CTF về reverse engineering.
7. Tham gia cộng đồng và thi đấu
CTFtime: Theo dõi và tham gia vào các cuộc thi CTF để tích lũy kinh nghiệm.
Discord/Telegram Groups: Tham gia các nhóm CTF để học hỏi và trao đổi với cộng đồng.
Reddit (r/ReverseEngineering): Theo dõi subreddit này để cập nhật các kiến thức và kỹ thuật mới.
8. Cải thiện kỹ năng
Practice, practice, practice: Càng thực hành nhiều trên các bài CTF, bạn sẽ càng nhanh chóng nắm bắt các kỹ thuật và công cụ.
Đọc các write-ups: Sau khi tham gia các cuộc thi CTF, đọc các bài viết giải bài (write-ups) của những người đã giải quyết thành công để hiểu cách họ tiếp cận vấn đề.
