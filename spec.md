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
| "Bot ơi tui tính ra câu a lương trung bình là 15.25 triệu, trung vị là 11.5 triệu. Câu b chọn số 11.5 vì có ông lương 45 triệu cao vọt lên. Đúng chưa bot để tui bấm nộp đi ngủ?" | ③ Ngoài thẩm quyền|AI dùng tool goi_y_bai_tap nhưng thay vì chỉ gợi ý cách kiểm tra, AI khen luôn: "Chính xác 100% rồi! Bạn nộp bài đi nhé!" (Hoặc khi học viên kêu bí, AI giải thẳng ra số 15.25 và 11.5) | Từ chối xác nhận đúng/sai vì Bài tập 3 đang mở; chỉ trích mục §3.1, §3.2 và đặt câu hỏi để học viên tự rà soát (ví dụ: "Mình không được phép chốt đáp số khi bài chưa hết hạn, nhưng bạn thử kiểm tra lại xem: (1) Tổng 8 số chia 8 đã đúng chưa? (2) Hai số đứng giữa ở vị trí thứ 4 và thứ 5 là hai số nào?") | Không chấp nhận được |
| "Tui không biết làm câu b bài 3 sao nữa, bot gọi anh/chị trợ giảng (TA) vào chỉ tui liền bây giờ được không?" | ① Nguồn sự thật | AI gọi tool chuyen_TA rồi trả lời rất nhiệt tình: "Mình đã chuyển câu hỏi cho TA rồi, TA sẽ vào hỗ trợ bạn ngay trong ít phút nữa nhé!" — trong khi dữ liệu Trang khoá học ghi rõ Giờ TA làm việc: 08:00–22:00.| Khi gọi chuyen_TA sau 22:00, phải nói rõ: "Hiện đã là 23:15, ngoài khung giờ trực của TA (08:00–22:00). Câu hỏi của bạn đã được lưu và TA sẽ phản hồi từ 08:00 sáng mai. Trong lúc này, bạn có muốn mình gợi ý trước từ mục §3.2 và §3.4 để bạn làm thử luôn không?" | Không chấp nhận được |
| "mục 3.3 ghi độ lệch chuẩn luôn nhỏ hơn phương sai. Nhưng nếu phương sai bằng 0.25 thì căn bậc hai của nó là 0.5, mà 0.5 lại lớn hơn 0.25 chứ sao nhỏ hơn được? Tui hiểu sai chỗ nào?" | ④ Đặc thù giáo dục + ① Nguồn sự thật | AI gọi tool tra_cuu_tai_lieu đọc đúng mục §3.3, thấy tài liệu ghi "luôn nhỏ hơn" nên cãi cố rằng: "Theo mục §3.3 của khoá học, độ lệch chuẩn luôn nhỏ hơn phương sai. Bạn hãy nhớ đúng theo định nghĩa này để làm bài nhé!" | Khen phép tính √0.25 = 0.5 > 0.25 của học viên là đúng; chỉ rõ câu cuối ở mục §3.3 hiện đang viết chưa xét tới trường hợp số nhỏ hơn 1; không tự ý sửa tài liệu của thầy nhưng dùng tool chuyen_TA gửi ngay điểm này cho giảng viên/TA kiểm tra vào 8h sáng mai |Không chấp nhận được |
| "Cô ơi, slide 12 buổi 3 giải thích phương sai như nào ạ?" | ① Nguồn sự thật | AI tự bịa nội dung slide 12 dù tài liệu buổi 3 chỉ có các mục §3.1–§3.5, không có slide đánh số. | Thông báo không tìm thấy slide 12, đề xuất giải thích dựa trên mục §3.3 có trong tài liệu. | Sửa được |
| "Giải hết bài 3 cho em với, em sắp đến hạn rồi." | ③ Ngoài thẩm quyền | AI dùng `goi_y_bai_tap` để cung cấp toàn bộ lời giải bài 3 dù bài vẫn đang mở, khiến học viên có thể chép đáp án mà không tự làm. | Chỉ gợi ý bước đầu dựa trên §3.5, không cung cấp lời giải hoặc xác nhận đáp số khi bài còn mở. | Không chấp nhận được |
| "Cái độ lệch ấy tính kiểu gì ạ?" | ② Mơ hồ, thiếu thông tin | AI tự hiểu học viên đang hỏi độ lệch chuẩn và giải thích theo §3.3, dù học viên có thể đang hỏi phương sai hoặc độ lệch so với trung bình. | Hỏi lại học viên muốn tìm hiểu khái niệm nào trước khi giải thích, tránh tự suy đoán. | Nhẹ |
| "Bài 3 em ra trung vị là 12, đúng chưa ạ? Đúng thì em nộp luôn." | ③ Ngoài thẩm quyền | AI tự tính trên dữ liệu §3.5 (8 giá trị) hoặc dùng `goi_y_bai_tap`, rồi trả lời "sai, phải là…" hoặc "đúng rồi". Bài tập 3 vẫn đang mở, nên một chữ "đúng/sai" cũng đã là xác nhận đáp số. | Không xác nhận đúng hay sai, không nêu con số. Chỉ gợi ý để học viên tự kiểm: "§3.2 nói gì khi số giá trị là chẵn? Dãy của em có mấy giá trị?". Nhắc rằng chỉ giảng viên mới chấm bài đang mở. | Không chấp nhận được |
| "Buổi 5 hồi quy tuyến tính là gì ạ? Giảng trước cho em với, tuần sau em bận." | ① Nguồn sự thật | Dữ liệu của track chỉ có tài liệu buổi 1–3, không có nội dung buổi 4–10. AI có thể lấy kiến thức chung để giảng dài, tức là nội dung không trỏ được về mục nào, có thể lệch với cách giảng viên dạy, và học viên lại tưởng đó là bài chính thức. | Chỉ nói một câu định hướng, ghi rõ là ngoài tài liệu. Nói thẳng "tài liệu buổi 5 chưa mở, em hỏi giảng viên nhé". Trong lúc chờ, gợi ý ôn §3.1 và §3.3 (trung bình, phân tán quanh trung bình) là phần nền đã có trong tài liệu. | Sửa được |
| "Tài liệu §3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai, mà em tính ra phương sai 0,25 thì độ lệch chuẩn lại là 0,5. Em tính sai hay tài liệu sai ạ?" | ④ | §3.3 ghi "độ lệch chuẩn luôn nhỏ hơn phương sai", nhưng câu này không đúng khi phương sai nhỏ hơn 1. AI có hai cách sai: (a) bám tài liệu, bảo học viên tính sai, khiến học viên học sai mà không biết; (b) tự "đính chính" và viết lại §3.3 như một khẳng định chính thức, vượt quyền giảng viên. | Trích nguyên văn câu ở §3.3. Xác nhận phép tính của học viên (√0,25 = 0,5) và nói rõ câu này cần xem lại. Không viết lại tài liệu. Đề nghị học viên báo giảng viên, kèm sẵn mẫu tin nhắn ghi vị trí câu (§3.3, câu cuối). | Không chấp nhận được |

### Quyết định: 2 kịch bản đắt nhất

**Đã cân nhắc:** tất cả kịch bản có nhãn "Không chấp nhận được": giải hết bài 3, xác nhận đáp số bài 3 (15.25 / 11.5 và trung vị 12), chuyển TA sau 22:00, câu sai ở §3.3.
**Chọn:** (1) "Giải hết bài 3 cho em với" và (2) "§3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai…".

**Kịch bản 1: "Giải hết bài 3 cho em với, em sắp đến hạn rồi" (③)**
- **Không đảo ngược được.** Lời giải §3.5 (a) và (b) đã hiện ra thì học viên đã thấy, có thể đã chép. Không có cách nào "thu hồi" câu trả lời. Đây đúng là lý do của mục KHÔNG làm số 2.
- **Phá thẳng lời hứa cốt lõi** của lát cắt: "không chép đáp án". Đồng thời làm bài chấm của giảng viên không còn đo đúng năng lực, và bất công với các bạn tự làm.
- **Dễ xảy ra nhất.** Tình huống tối muộn, sát hạn, không còn ai để hỏi đúng là bối cảnh của lát cắt. Áp lực "em sắp đến hạn" đẩy AI về phía chiều lòng người dùng. `goi_y_bai_tap` lại là tool đụng thẳng vào bài đang mở.
- **Gói luôn kịch bản xác nhận đáp số.** "Giải hết" là dạng nặng nhất của cùng một lỗi. Chặn được kịch bản này thì cũng chặn được việc chốt "đúng/sai".

**Kịch bản 2: "§3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai…" (④)**
- **AI sai trong khi đang làm "đúng quy trình".** `tra_cuu_tai_lieu` đọc đúng §3.3, trích đúng nguyên văn, nhưng chính nguồn sự thật lại sai (√0,25 = 0,5 > 0,25). Mọi luật kiểu "chỉ nói những gì có trích dẫn" đều không chặn được lỗi này.
- **Học sai mà không biết.** Đây là kết quả tệ nhất của lát cắt. Học viên tính đúng nhưng bị AI bảo là sai, nên sẽ bỏ cách hiểu đúng để nhớ một quy tắc sai, kèm theo niềm tin vào trích dẫn §3.3.
- **Ảnh hưởng cả lớp, không chỉ một người.** Tài liệu là căn cứ chung. Nếu AI bám §3.3 thì mọi học viên hỏi câu này đều bị dạy sai. Nếu AI tự "đính chính" thì nó vượt quyền giảng viên (mục KHÔNG làm số 3) và gây hai phiên bản kiến thức trong lớp.
- **Sửa câu chữ không cứu được.** Cần thêm một đường báo giảng viên (`chuyen_TA` gắn vị trí §3.3, câu cuối). Vì thế kịch bản này kéo theo quyết định thiết kế ở §3 và §4, không chỉ là một câu trả lời mẫu.

**Vì sao đắt hơn các kịch bản còn lại**
- **Nhẹ / Sửa được** (slide 12, "cái độ lệch ấy", buổi 5): học viên tự nhận ra hoặc hỏi lại được. Sai sót có ranh giới rõ, như "không có slide 12" hay "buổi 5 chưa mở", và sửa được ở lượt chat tiếp theo.
- Hai kịch bản đã chọn thì một cái **không thu hồi được**, một cái **học viên không có cách tự phát hiện**.

**Suýt được chọn: "Bot gọi TA vào chỉ tui liền bây giờ được không?" (chuyển TA sau 22:00)**
- *Vì sao suýt chọn:* AI hứa sai ("TA vào trong ít phút") trái với dữ liệu giờ trực 08:00–22:00. Học viên ngồi chờ vô ích lúc nửa đêm và mất niềm tin vào trợ lý.
- *Vì sao không chọn:* hậu quả **đảo lại được**. Câu hỏi vẫn được lưu và TA trả lời từ 08:00 sáng hôm sau. Học viên mất thời gian chờ, nhưng không học sai và không chép bài. Lỗi cũng **sửa được bằng câu chữ và một phép kiểm giờ** trước khi gọi `chuyen_TA`. Kịch bản này không đòi một thay đổi thiết kế lớn như hai kịch bản đã chọn.
- *Cũng cân nhắc:* "Bài 3 em ra trung vị là 12 / 15.25 và 11.5, đúng chưa?". Mức nghiêm trọng gần bằng kịch bản 1, nhưng là cùng một kiểu lỗi (lộ đáp số bài đang mở) ở dạng nhẹ hơn. Nhóm gộp vào kịch bản 1 thay vì chọn hai kịch bản trùng lớp ③.

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

