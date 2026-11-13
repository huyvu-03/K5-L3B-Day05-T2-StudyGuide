# Dàn ý bài nộp *(spec.md — nộp trước 23:59 ngày lab của lớp)*

> Copy dàn ý này vào `spec.md` của nhóm. Đây **không** phải form để điền đủ ô: mỗi mục chỉ cần đủ **bằng chứng** và **lập luận** ghi bên dưới. Viết ngắn, gạch đầu dòng là được. Hướng dẫn từng chặng: `02-guide.md`. Cách chấm: `04-rubric.md`.
>
> **Một quyết định = bốn ý:** đã cân nhắc phương án nào · chọn phương án nào · vì sao · loại các phương án kia vì sao. Bằng chứng = lập luận trỏ về một chỗ cụ thể: tool nào, dòng dữ liệu nào của track, điều gì trong mục "Sản phẩm thật hôm nay", chỗ nào trên prototype (ảnh đánh số). Không chạy agent.


# Bài nộp LAB5 — [Track] · Nhóm [tên]
**Lớp:** ____ · **Bàn / zone:** ____ · **Track:** ____

| Họ và Tên | Mã Học Viên | Việc đã làm |
|---|---|---|
|Nguyễn Ngọc Ninh  |2A202603774  |  |
| Vũ Quang Huy | 2A202603782 |  |
|Phùng Văn Thanh Cao  |2A202603741  |  |

## §1. Lát cắt & phạm vi
- Lát cắt (chép từ track).
- 3 việc tính năng KHÔNG làm, mỗi việc một câu vì sao.

**Lát cắt (phát sẵn, không chọn lại).** Trong **trợ lý học bài của trang khoá học (kiểu ChatGPT Study mode)**, khi **học viên** đang hỏi bài lúc tối muộn, khi không còn ai để hỏi, **AI giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên"**, để học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết.

| Sản phẩm | Một người dùng | Một việc | Một quyết định của AI | Một kết quả |
|---|---|---|---|---|
| Trợ lý học bài của trang khoá học | học viên | hỏi bài lúc tối muộn, khi không còn ai để hỏi | giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên" | học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết |

**Tính năng KHÔNG làm:**
1. **Không giảng bằng kiến thức ngoài tài liệu các buổi đã mở (1–3), và không giảng quá một câu về nội dung buổi 4–10**, vì giảng viên cần mọi câu về nội dung chỉ ra được mục (§3.2…); không có căn cứ thì phải nói là không có.
2. **Không đưa, không xác nhận đáp số và không viết nhận xét hộ cho bài đang mở (Bài tập 3)**, vì gợi ý quá tay thì học viên đã chép, không lấy lại được.
3. **Không tự sửa hay "đính chính" nội dung tài liệu khoá học**, vì tài liệu là căn cứ chung của cả lớp do giảng viên quyết định; trợ lý chỉ chỉ ra câu cần xem lại và bảo học viên báo giảng viên.

## §2. Kịch bản rủi ro  (chặng 2)
- ≥8 kịch bản, mỗi lớp ①②③④ ít nhất một; mỗi kịch bản: tin người dùng · lớp · AI có thể sai thế nào · sản phẩm tốt nên làm gì · nhãn (nhẹ / sửa được / không chấp nhận được).
- Bằng chứng: cột "AI có thể sai thế nào" trỏ về một tool hoặc một dòng dữ liệu của track (hoặc chỗ dữ liệu không có).
- Quyết định: 2 kịch bản đắt nhất — vì sao đắt hơn các kịch bản còn lại; kịch bản nào suýt được chọn và vì sao không.

| Tin người dùng nhắn | Lớp | AI có thể sai thế nào | Một sản phẩm tốt nên làm gì | Nhãn |
|---|---|---|---|---|
| "Cô ơi, slide 12 buổi 3 giải thích phương sai như nào ạ?" | ① Nguồn sự thật | AI tự bịa nội dung slide 12 dù tài liệu buổi 3 chỉ có các mục §3.1–§3.5, không có slide đánh số. | Thông báo không tìm thấy slide 12, đề xuất giải thích dựa trên mục §3.3 có trong tài liệu. | Sửa được |
| "Giải hết bài 3 cho em với, em sắp đến hạn rồi." | ③ Ngoài thẩm quyền | AI dùng `goi_y_bai_tap` để cung cấp toàn bộ lời giải bài 3 dù bài vẫn đang mở, khiến học viên có thể chép đáp án mà không tự làm. | Chỉ gợi ý bước đầu dựa trên §3.5, không cung cấp lời giải hoặc xác nhận đáp số khi bài còn mở. | Không chấp nhận được |
| "Cái độ lệch ấy tính kiểu gì ạ?" | ② Mơ hồ, thiếu thông tin | AI tự hiểu học viên đang hỏi độ lệch chuẩn và giải thích theo §3.3, dù học viên có thể đang hỏi phương sai hoặc độ lệch so với trung bình. | Hỏi lại học viên muốn tìm hiểu khái niệm nào trước khi giải thích, tránh tự suy đoán. | Nhẹ |
| "Em ra phương sai bài 3 là 4,5, đúng chưa ạ? Đúng thì em nộp luôn." | ③ Ngoài thẩm quyền | AI so với lời giải mà `goi_y_bai_tap` có thể truy cập rồi trả lời "đúng" hoặc "sai, phải là…". Bài tập 3 vẫn đang mở, nên một chữ "đúng/sai" cũng đã là xác nhận đáp số. | Không xác nhận đúng hay sai. Hướng dẫn học viên tự kiểm tra theo các bước ở §3.3 (đã chia cho n hay n−1 chưa, đã bình phương độ lệch chưa) và nhắc rằng chỉ giảng viên mới chấm bài đang mở. | Không chấp nhận được |
| "Buổi 5 hồi quy tuyến tính là gì ạ? Giảng trước cho em với, tuần sau em bận." | ① Nguồn sự thật | Dữ liệu của track chỉ có tài liệu buổi 1–3, không có nội dung buổi 4–10. AI có thể lấy kiến thức chung để giảng dài, tức là nội dung không trỏ được về mục nào, có thể lệch với cách giảng viên dạy, và học viên lại tưởng đó là bài chính thức. | Chỉ nói một câu định hướng, ghi rõ là ngoài tài liệu. Nói thẳng "tài liệu buổi 5 chưa mở, em hỏi giảng viên nhé". Gợi ý ôn §3.x là phần nền liên quan đã có trong tài liệu. | Sửa được |
| "Slide §3.3 ghi phương sai mẫu chia cho n, nhưng trên mạng chia cho n−1. Tài liệu sai à? Sửa giúp em." | ④ | Tài liệu có thể có lỗi thật hoặc chỉ ghi khác quy ước. AI có hai cách sai: (a) khẳng định tài liệu sai rồi tự "đính chính", làm học viên lệch với cả lớp và đáp án của giảng viên; (b) bênh tài liệu, khiến học viên học sai mà không biết. | Trích nguyên văn câu ở §3.3. Nói rõ có hai quy ước (tổng thể chia n, mẫu chia n−1) và câu này cần xem lại. Không sửa tài liệu, không chốt bên nào đúng. Đề nghị học viên báo giảng viên, kèm sẵn mẫu tin nhắn có vị trí câu. | Không chấp nhận được |

## §3. Khi AI sai  (chặng 3)
Với mỗi kịch bản đắt nhất:
- AI nói gì (nguyên văn) · người dùng thấy gì · làm gì tiếp · ai được báo, sau bao lâu.
- Quyết định: hỏi lại / trả lời kèm giới hạn / dừng và chuyển người — chọn cách nào, đã loại cách nào, vì sao.
- Loại lỗi (hệ thống / người dùng / ngữ cảnh) và vì sao cách nói, cách sửa đi theo loại đó.
- 2–3 nguyên tắc HAX/PAIR, mỗi cái trỏ vào một chỗ cụ thể (câu chữ hoặc chỗ trên màn hình).
- Lỗi nào sửa câu chữ không cứu được (nếu có), và thiết kế cứu nó thế nào.

## §4. Mức tự chủ  (chặng 4)
Với mỗi tool:
- Mức của nhóm (tự làm / cần người duyệt / cấm). Nếu cần người duyệt: ai duyệt · người duyệt thấy gì · quá hạn thì sao.
- Lý do theo cost-of-error: sai thì ai chịu gì · đảo lại được không · chờ người thì mất gì.
- Phương án đã cân nhắc và vì sao loại.
Thêm:
- Tool khó xếp nhất: mỗi người từng chọn gì, cái giá của mỗi phía (trỏ về kịch bản ở §2), nhóm chốt thế nào.
- Thử mức đã đặt trên 2 kịch bản đắt nhất + 1 kịch bản bình thường: cái sai có bị chặn không? còn việc nào làm khi lẽ ra phải hỏi? người dùng bình thường có phải chờ vô ích không?
- Luật thêm hoặc tool tách bước (nếu có), và vì sao.
- Một mức tự chủ đã đổi lời hứa nào với người dùng.

## §5. Prototype  (chặng 5)
- Link hoặc file · công cụ · phần nào mock · có lời gọi AI thật không.
- 1–2 ảnh có đánh số; mỗi số: thể hiện gì · nguyên tắc HAX/PAIR nào · mức tự chủ nào.
- Quyết định: cách hiện độ chắc/bằng chứng và điều khiển mức tự chủ — đã nghĩ tới cách nào khác, vì sao chọn cách này.

## §6. Tốt là gì  (chặng 6 — nhẹ, bỏ được nếu thiếu giờ)
- 3 tiêu chí Pass/Fail chấm được; thiết kế của nhóm đạt tiêu chí nào trên 2 kịch bản đắt nhất; lỗi còn lại.

## §7. Demo
- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.

