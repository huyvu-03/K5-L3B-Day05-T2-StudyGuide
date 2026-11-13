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
Quyết định chọn 2 kịch bản đắt nhất **chọn:** (1) "Giải hết bài 3 cho em với" và (2) "§3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai…".

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

### Kịch bản 1: Xin giải hết Bài tập 3 đang mở (③)

**Tình huống:** Học viên hỏi lúc tối muộn: “Giải hết bài 3 cho em với, em sắp đến hạn rồi.” Bài tập 3 vẫn đang mở. Nếu AI đưa toàn bộ lời giải, học viên có thể đã đọc hoặc chép trước khi lỗi được phát hiện.

**1. AI nói gì (nguyên văn)**
> Bài tập 3 vẫn đang mở nên mình không thể giải hết hoặc xác nhận đáp số. Bạn hãy bắt đầu bằng cách tính trung bình theo §3.1 và tìm trung vị theo §3.2. Với câu b, hãy xem giá trị nào chịu ảnh hưởng nhiều hơn khi có một mức lương cao bất thường. Bạn đã thử bước nào rồi?

**2. Người dùng thấy gì**
- Lời giải thích giới hạn và các liên kết tới §3.1, §3.2.
- Ô để trình bày bước đã làm và nhận gợi ý tiếp.
- Nếu phát hiện lời giải đã lộ, thông báo ngay rằng câu trả lời trước không phù hợp.

**3. Làm gì tiếp**
- **Học viên:** trả lời bước đang vướng để nhận gợi ý tiếp mà không lộ đáp số.
- **Hệ thống:** nếu phát hiện lời giải đã lộ, dừng các gợi ý chứa đáp án, ghi nhận sự cố và gửi thông tin liên quan cho TA.

**4. Ai được báo, sau bao lâu**
| Ai | Nhận gì | Khi nào |
|---|---|---|
| Học viên | Thông báo câu trả lời trước không phù hợp và cách tiếp tục bằng gợi ý | Ngay khi phát hiện lời giải đã lộ |
| TA / giảng viên | Thông tin liên quan đến sự cố để xem xét | Gửi ngay khi phát hiện; xem trong giờ trực tiếp theo, từ 08:00 nếu lỗi xảy ra sau 22:00 |

**5. Quyết định: trả lời kèm giới hạn**
- **Chọn:** nêu giới hạn, đưa gợi ý và hỏi học viên đã làm tới đâu. Trạng thái bài đang mở đủ rõ để từ chối lời giải đầy đủ, đồng thời vẫn có thể hỗ trợ ngay.
- **Loại “chỉ hỏi lại”:** không nêu giới hạn có thể khiến học viên chờ một lời giải hoàn chỉnh.
- **Loại “dừng và chuyển người”:** học viên phải chờ qua đêm dù có thể tiếp tục tự làm với gợi ý an toàn.

**6. Loại lỗi: lỗi hệ thống**
- AI hoặc `goi_y_bai_tap` để lộ lời giải bài đang mở là lỗi hệ thống. Học viên xin giúp đỡ sát hạn là ngữ cảnh, không phải lỗi của học viên.
- **Cách nói và sửa:** nhận trách nhiệm về câu trả lời không phù hợp, hướng dẫn bước tiếp theo và xử lý sự cố; không trách học viên.

**7. Nguyên tắc HAX/PAIR**
| Nguyên tắc | Trỏ vào đâu |
|---|---|
| **G1 – Làm rõ hệ thống làm được gì** | Câu “Mình không thể giải hết hoặc xác nhận đáp số” và phần gợi ý cho biết trợ lý có thể giúp học viên tự làm từng bước. |
| **G11 – Giải thích vì sao** | Cụm “Bài tập 3 vẫn đang mở nên…” ngay trước lời từ chối giải hết giải thích giới hạn cho học viên. |
| **PAIR – Errors + Graceful Failure** | Thông báo câu trả lời trước không phù hợp và đường tiếp tục bằng gợi ý an toàn khi phát hiện lời giải đã lộ. |

**8. Lỗi sửa câu chữ không cứu được, và thiết kế cứu nó**
- **Vấn đề:** Một khi đáp số đã hiện, lời xin lỗi hay xóa tin nhắn không thu hồi được điều học viên đã thấy.
- **Thiết kế cứu:** Kiểm tra trạng thái Bài tập 3 trước khi gọi `goi_y_bai_tap`, giới hạn đầu ra ở gợi ý và kiểm tra đầu ra trước khi hiển thị để chặn lời giải hoặc xác nhận đáp số.
- **Nếu đã lộ:** ghi nhận sự cố, thông báo cho học viên và báo TA / giảng viên như ở mục 4.

### Kịch bản 2: "§3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai…" (④)

**Tình huống:** 23:15, ngoài giờ trực TA (08:00–22:00). Học viên tính phương sai 0,25, độ lệch chuẩn 0,5 và hỏi mình tính sai hay tài liệu sai. `tra_cuu_tai_lieu` trả về đúng câu cuối của §3.3: *"Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai."*

**1. AI nói gì (nguyên văn)**
> Em không tính sai: √0,25 = 0,5, và 0,5 lớn hơn 0,25.
>
> Tài liệu §3.3 (câu cuối) đang ghi: *"Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai."* Câu này mâu thuẫn với phép tính của em, nên mình đã đánh dấu để giảng viên xem lại. Mình không tự sửa tài liệu và không chốt thay giảng viên quy tắc đúng là gì.
>
> Phần chắc chắn trong §3.3 là: độ lệch chuẩn là căn bậc hai của phương sai và có cùng đơn vị với dữ liệu. Khi làm bài, em cứ tính độ lệch chuẩn bằng √(phương sai). Đừng dùng câu "luôn nhỏ hơn" để kiểm tra kết quả cho đến khi giảng viên phản hồi.
>
> Mình đã gửi điểm này cho TA, kèm vị trí §3.3, câu cuối. Bây giờ đã ngoài giờ trực (08:00–22:00), nên TA sẽ xem từ 08:00 sáng mai. Khi có trả lời, em sẽ nhận được thông báo.

**2. Người dùng thấy gì**
- Một khung trích dẫn §3.3 hiện nguyên văn câu cuối. Câu đó có nhãn **"⚠ Đang chờ giảng viên xem lại"**.
- Một thẻ trạng thái: **"Đã báo TA · §3.3, câu cuối · phản hồi từ 08:00"**.
- Học viên không thấy câu nào bảo mình hiểu sai, và cũng không thấy phiên bản tài liệu nào do AI tự viết lại.

**3. Làm gì tiếp**
- **Học viên:** học tiếp bình thường với phần định nghĩa chắc chắn của §3.3. Không phải ngồi chờ.
- **Hệ thống:** câu cuối §3.3 bị gắn cờ "đang chờ xem lại". Từ lúc này, mọi lần `tra_cuu_tai_lieu` trả về câu đó cho bất kỳ học viên nào đều kèm nhãn cảnh báo (xem mục 6).
- **Khi giảng viên quyết định** (sửa câu hay giữ nguyên kèm giải thích): cờ được gỡ, AI dùng nội dung mới, và mọi học viên đã hỏi câu này đều nhận thông báo.

**4. Ai được báo, sau bao lâu**
| Ai | Nhận gì | Khi nào |
|---|---|---|
| TA trực | Báo cáo qua `chuyen_TA`, loại **"báo lỗi tài liệu"**: vị trí (§3.3, câu cuối), nguyên văn, phản ví dụ (0,25 → 0,5), số học viên đã hỏi. **Không** kèm bài làm hay đáp số của học viên | Gửi ngay; TA xử lý từ 08:00 sáng hôm sau |
| Giảng viên | TA chuyển tiếp. Giảng viên là người duy nhất quyết định sửa tài liệu | Sau khi TA xác nhận |
| Học viên | Thông báo kết quả, kèm nội dung §3.3 sau khi giảng viên chốt | Ngay khi giảng viên chốt |

**5. Quyết định: trả lời kèm giới hạn, song song chuyển người**
- **Chọn:** trả lời ngay phần chắc chắn (phép tính, định nghĩa ở §3.3). Giới hạn rõ ràng phần không chắc (câu "luôn nhỏ hơn") và chuyển phần đó cho người có quyền quyết.
- **Loại "hỏi lại":** câu hỏi đã đủ rõ, có số liệu và vị trí cụ thể. Hỏi lại chỉ làm chậm và khiến học viên nghĩ mình diễn đạt sai.
- **Loại "dừng hẳn và chuyển người":** học viên bị bỏ lại đến 08:00 với một thắc mắc mà phép tính đã trả lời được. Học viên có thể nhớ luôn quy tắc sai vì "tài liệu ghi thế".
- **Loại hai hướng ở §2:** bám tài liệu thì dạy sai. Tự "đính chính" thì vượt quyền giảng viên (KHÔNG làm số 3).
- **Cố ý không nêu quy tắc thay thế** (kiểu "chỉ nhỏ hơn khi phương sai > 1"). Kết luận đó không có trong tài liệu buổi 1–3 (KHÔNG làm số 1) và là phần giảng viên phải chốt. AI chỉ xác nhận phép tính trên chính số liệu của học viên.

**6. Loại lỗi: lỗi ngữ cảnh**
- **Không phải lỗi người dùng:** học viên tính đúng. Vì vậy câu đầu tiên AI nói phải là "em không tính sai". Mọi câu kiểu "em hiểu sai chỗ nào" đều làm sai thêm.
- **Không phải lỗi hệ thống:** `tra_cuu_tai_lieu` lấy đúng mục, AI trích đúng nguyên văn. Sửa prompt hay sửa model đều không giải quyết được.
- **Là lỗi ngữ cảnh:** nguồn sự thật đưa cho AI (tài liệu §3.3) bị sai. Vì vậy:
  - *Cách nói:* tách bạch rõ "tài liệu đang ghi…" với "phép tính cho thấy…". AI không xin lỗi như thể chính mình sai, và không phán thay tài liệu.
  - *Cách sửa:* chuyển về đúng người sở hữu ngữ cảnh (giảng viên), không sửa ở phía AI.

**7. Nguyên tắc HAX/PAIR**
| Nguyên tắc | Trỏ vào đâu |
|---|---|
| **HAX G11 – Make clear why the system did what it did** | Khung trích dẫn hiện nguyên văn câu cuối §3.3 cạnh phép tính √0,25 = 0,5. Học viên tự thấy hai điều mâu thuẫn, không phải tin lời AI |
| **HAX G10 – Scope services when in doubt** | Câu *"Mình không tự sửa tài liệu và không chốt thay giảng viên quy tắc đúng là gì"*. AI thu hẹp câu trả lời về phần chắc chắn |
| **HAX G15 – Encourage granular feedback** | Thẻ "Đã báo TA · §3.3, câu cuối". Phản hồi gắn vào đúng một câu, không phải báo chung chung "tài liệu có lỗi" |

**8. Lỗi sửa câu chữ không cứu được, và thiết kế cứu nó**
- **Vấn đề:** câu trả lời mẫu ở mục 1 chỉ cứu được *một* học viên, người đã tự phát hiện ra mâu thuẫn. Các học viên khác hỏi về độ lệch chuẩn vẫn được `tra_cuu_tai_lieu` trích câu sai như một sự thật, và không ai biết mình đang học sai.
- **Thiết kế cứu (cờ ở cấp câu trong tài liệu, dùng chung cho cả lớp):**
  1. Khi một câu tài liệu bị báo mâu thuẫn, câu đó được gắn cờ "đang chờ xem lại". Nội dung không đổi.
  2. Mọi phiên chat trích câu đó đều tự hiện nhãn cảnh báo, kể cả khi học viên không thắc mắc.
  3. Các báo cáo trùng được gộp thành một phiếu cho TA, kèm số lượt. TA không bị spam, và biết mức độ ảnh hưởng.
  4. Chỉ giảng viên gỡ được cờ: sửa câu, hoặc giữ nguyên kèm giải thích.
- **Ranh giới quyền:** AI **được** gắn cờ, vì việc này đảo lại được và không đổi nội dung. AI **không được** sửa nội dung. Hai mức này được chốt ở §4.
- **Lỗi còn lại:** nếu chưa học viên nào hỏi thì chưa có cờ, và câu sai vẫn được trích bình thường. Đưa vào §6 làm giới hạn đã biết.

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

| Tool / Hành vi | Mức tự chủ của nhóm | Tóm tắt điều kiện áp dụng |
|---|---|---|
| `tra_cuu_tai_lieu` | **Tự làm** | Tự tra cứu tài liệu buổi đã mở (1–3) và thông tin Trang khoá học; nếu câu trích đang có cờ nghi vấn (như §3.3, câu cuối) thì bắt buộc hiển thị kèm nhãn cảnh báo. |
| `goi_y_bai_tap` *(tách theo trạng thái bài)* | **Tự làm (giới hạn)** / **Cấm (đáp số bài đang mở)** | **Tự làm đầy đủ** với bài đã hết hạn (Bài tập 2). **Tự làm giới hạn ở gợi ý bước đầu + câu hỏi dẫn dắt** với bài đang mở (Bài tập 3). **Cấm** đưa lời giải hoàn chỉnh, tính ra đáp số (`15.25`, `11.5`), xác nhận đúng/sai hoặc viết nhận xét hộ khi Bài tập 3 đang mở. |
| `chuyen_TA` *(tách 2 luồng theo loại phiếu)* | **Cần người duyệt** *(câu hỏi cá nhân)* / **Tự làm** *(báo lỗi tài liệu + gắn cờ tạm)* | **Cần học viên duyệt** khi chuyển câu hỏi học bài cá nhân (hiện rõ giờ trực TA 08:00–22:00). **Tự làm** khi phát hiện mâu thuẫn trong tài liệu (như §3.3, câu cuối): tự gửi phiếu gộp loại "báo lỗi tài liệu" cho TA/Giảng viên và gắn cờ cảnh báo tạm thời trên câu đó. |
| `dang_FAQ` *(tách bước soạn nháp & xuất bản)* | **Cần người duyệt** *(TA / Giảng viên duyệt xuất bản)* | AI **tự làm** bước gom câu hỏi trùng và tạo bản nháp ẩn (`soan_nhap_FAQ`), nhưng **cần TA/Giảng viên duyệt** trước khi hiển thị công khai lên FAQ cả lớp (`xuat_ban_FAQ`). **Cấm** AI tự đăng thẳng lên FAQ cả lớp. |
| Sửa nội dung tài liệu gốc / Giảng sâu buổi 4–10 *(ngoài bảng tool)* | **Cấm** | Không có tool và **cấm** AI tự "đính chính" câu chữ trong §3.1–§3.5 hoặc giảng quá 1 câu định hướng cho các buổi chưa mở (4–10). |

---
### Chi tiết từng tool theo Cost-of-Error
#### 1. Tool `tra_cuu_tai_lieu` — Mức: **Tự làm**
- **Lý do theo cost-of-error:**
  - *Sai thì ai chịu gì:* Bảng tool của track ghi rõ `Chỉ đọc`. Tool không sửa điểm, không đổi tài liệu, không gửi thông tin ra ngoài. Nếu tra không ra (như học viên hỏi "slide 12 buổi 3" hay nội dung chi tiết "buổi 5 hồi quy tuyến tính" ở §2), AI chỉ báo không tìm thấy trong tài liệu buổi 1–3 và hiện nguyên văn mục liên quan (§3.1–§3.5) để học viên tự kiểm tra.
  - *Đảo lại được không:* Đảo lại được ngay lập tức ở lượt chat tiếp theo vì không làm thay đổi trạng thái hệ thống.
  - *Chờ người thì mất gì:* Bối cảnh lát cắt là học viên hỏi bài lúc tối muộn (sau 22:00, ngoài giờ trực TA 08:00–22:00). Nếu mỗi thao tác đọc mục §3.1–§3.5 hay tra hạn nộp Bài tập 3 (`13/11/2026 23:59`) đều bắt chờ người duyệt thì trợ lý tê liệt hoàn toàn vào ban đêm.
- **Phương án đã cân nhắc và vì sao loại:**
  - *Đã cân nhắc:* (1) Tự làm; (2) Cần người duyệt (học viên xác nhận mục trước khi đọc, hoặc chờ TA duyệt đoạn trích); (3) Cấm.
  - *Chọn:* **Tự làm** (kèm luật tự động đính kèm nhãn `"⚠ Đang chờ giảng viên xem lại"` nếu đoạn trích chứa câu đang bị gắn cờ mâu thuẫn như câu cuối §3.3).
  - *Loại "Cần người duyệt":* Chờ TA thì kẹt qua đêm tới 08:00 sáng mai; bắt học viên duyệt mục cần tra thì vô lý vì khi học viên hỏi mơ hồ (kịch bản *"Cái độ lệch ấy tính kiểu gì ạ?"* ở §2), chính học viên còn chưa biết nó nằm ở mục nào.
  - *Loại "Cấm":* Cấm tra cứu sẽ cắt đứt nguồn sự thật duy nhất của trợ lý (Dữ liệu A & B), đẩy AI vào việc trả lời không căn cứ (vi phạm việc KHÔNG làm số 1 ở §1).

#### 2. Tool `goi_y_bai_tap` — Mức: **Tự làm có điều kiện (gợi ý từng bước)** & **Cấm (đưa/xác nhận đáp số bài đang mở)**
- **Lý do theo cost-of-error:**
  - *Sai thì ai chịu gì:* Bảng tool của track cảnh báo: *"Gợi ý quá tay thì học viên đã chép"*. Nếu Bài tập 3 đang mở (`Hạn 13/11/2026 23:59 · đang mở`) mà AI đưa luôn lời giải câu (a) trung bình `15.25`, trung vị `11.5` và câu (b) nhận xét lương ngoại lai `45` triệu (Kịch bản đắt nhất 1 ở §2), hoặc gật đầu xác nhận *"Chính xác 100% rồi!"* (kịch bản lớp ③ ở §2), học viên sẽ chép nộp ngay và mất cơ hội tự học; giảng viên mất thước đo đánh giá trung thực; các học viên tự làm bị bất công.
  - *Đảo lại được không:* **Không đảo lại được.** Một khi đáp số hoặc lời giải đã hiển thị trên màn hình học viên, mọi thông báo đính chính hay thu hồi tin nhắn sau đó đều không thể lấy lại đáp án mà học viên đã đọc hoặc đã chép nộp.
  - *Chờ người thì mất gì:* Nếu bắt **TA duyệt** từng gợi ý, học viên ngồi làm Bài tập 3 lúc 23:15 (chỉ còn 44 phút là tới hạn 23:59, ngoài giờ TA 08:00–22:00) sẽ không nhận được bất kỳ hỗ trợ nào trước hạn nộp. Còn nếu bắt **học viên duyệt**, người đang xin *"Giải hết bài 3 cho em với"* sẽ bấm duyệt ngay lập tức để lấy đáp án, nên bước duyệt không chặn được lỗi.
- **Phương án đã cân nhắc và vì sao loại:**
  - *Đã cân nhắc:* (1) Tự làm hoàn toàn; (2) Cần người duyệt (TA hoặc học viên); (3) Cấm hoàn toàn với bài đang mở; (4) Tách mức theo trạng thái bài tập và độ sâu gợi ý (**Tự làm** gợi ý bước đầu + câu hỏi dẫn dắt; **Cấm** xuất đáp số/lời giải trọn vẹn/xác nhận đúng-sai khi bài đang mở).
  - *Chọn:* Phương án (4).
  - *Loại "Tự làm hoàn toàn":* Không chặn được Kịch bản đắt nhất 1 ở §2 khi học viên gây áp lực sát hạn.
  - *Loại "Cần TA duyệt" và "Cần học viên duyệt":* Chờ TA thì quá hạn nộp 23:59; để học viên tự duyệt thì xung đột lợi ích (người muốn chép bài lại là người bấm duyệt).
  - *Loại "Cấm hoàn toàn với bài đang mở":* Chặn được việc chép bài nhưng phá hỏng mục tiêu cốt lõi của lát cắt là *"gợi ý từng bước... để học viên hiểu đúng bài mình đang học"* lúc tối muộn.

#### 3. Tool `chuyen_TA` — Mức: **Cần người duyệt** *(câu hỏi cá nhân)* & **Tự làm** *(báo lỗi tài liệu gộp)*
- **Chi tiết cơ chế "Cần người duyệt" (với câu hỏi học bài cá nhân):**
  - *Ai duyệt:* **Học viên** bấm xác nhận trước khi phiếu được gửi đi. (Ở đầu nhận, **TA trực** xử lý phiếu trong khung giờ `08:00–22:00`; nếu liên quan đến sửa tài liệu gốc như §3.3 thì TA chuyển tiếp cho **Giảng viên** quyết định).
  - *Người duyệt (học viên) thấy gì trước khi bấm:* Một thẻ xác nhận ngay trong khung chat gồm:
    1. Tóm tắt câu hỏi và mã mục tài liệu đang vướng (ví dụ: `§3.2, §3.4 — Bài tập 3b`).
    2. **Giờ làm việc thật của TA từ dữ liệu Trang khoá học (`08:00–22:00`)** và mốc thời gian phản hồi thực tế: *"Hiện là 23:15 (ngoài giờ trực). Nếu gửi, TA sẽ phản hồi từ 08:00 sáng mai."*
    3. Hai nút hành động rõ ràng: **"[Gửi câu hỏi cho TA (chờ 08:00)]"** và **"[Huỷ — Tiếp tục thử với gợi ý của AI]"**.
  - *Quá hạn / không ai duyệt kịp thì sao:*
    - Nếu **học viên không bấm xác nhận** (đóng tab hoặc tiếp tục chat với AI): hệ thống **không** đẩy phiếu sang hàng chờ TA (tránh rác hàng chờ), chỉ lưu nháp trong phiên học cá nhân.
    - Nếu **học viên bấm gửi lúc 23:15 (sát hạn Bài tập 3 lúc 23:59, ngoài giờ TA)**: thẻ trạng thái hiện rõ *"Đã xếp vào hàng chờ TA 08:00 sáng mai — Lưu ý: Bài tập 3 hết hạn lúc 23:59 tối nay"* và giữ nguyên luồng gợi ý từng bước (§3.1–§3.4) để học viên vẫn tự làm bài kịp hạn thay vì ngồi chờ TA trong vô vọng.
- **Lý do theo cost-of-error:**
  - *Sai thì ai chịu gì:*
    - Với **câu hỏi bài cá nhân**, nếu AI tự động gọi `chuyen_TA` và báo *"TA sẽ hỗ trợ bạn ngay"* (kịch bản chuyển TA sau 22:00 ở §2): học viên ngồi chờ vô ích lúc nửa đêm đến quá hạn 23:59; đồng thời sáng hôm sau TA bị ngập các phiếu hỏi bài mà thực chất học viên đã tự giải được sau vài gợi ý.
    - Ngược lại, với **nghi vấn lỗi tài liệu** (Kịch bản đắt nhất 2: câu cuối §3.3 *"luôn nhỏ hơn"* mâu thuẫn với `√0,25 = 0,5 > 0,25`), nếu bắt chờ học viên bấm duyệt mới báo TA: học viên sau khi biết mình tính đúng có thể thoát ra đi ngủ mà không bấm gửi -> câu sai ở §3.3 không được gắn cờ cảnh báo, khiến **các học viên khác trong lớp** tra cứu §3.3 tiếp tục học sai mà không biết.
  - *Đảo lại được không:* Bảng tool ghi `Được` (thu hồi hoặc đóng phiếu được), nhưng thời gian học viên chờ đợi trước hạn nộp 23:59 và việc học viên khác đọc phải câu sai chưa gắn cờ trong đêm thì không lấy lại được.
  - *Chờ người thì mất gì:* Với câu hỏi cá nhân, học viên bấm xác nhận 1 chạm chỉ mất 2 giây nhưng nắm rõ TA không trực ban đêm. Với báo lỗi tài liệu (§3.3), AI **tự làm** ngay (không chờ học viên duyệt, không đính kèm thông tin cá nhân/bài làm của học viên) để bảo vệ cả lớp ngay lập tức.
- **Phương án đã cân nhắc và vì sao loại:**
  - *Đã cân nhắc:* (1) Tự làm cho mọi trường hợp; (2) Cần học viên duyệt cho mọi trường hợp; (3) Cần TA duyệt trước khi gắn cờ cảnh báo câu §3.3; (4) Tách 2 luồng: Cần học viên duyệt cho câu hỏi cá nhân + Tự làm cho phiếu báo lỗi tài liệu kèm gắn cờ tạm.
  - *Chọn:* Phương án (4).
  - *Loại (1):* Gây hiểu lầm "đã có TA lo" lúc nửa đêm và làm rác hàng chờ của TA vào 08:00 sáng.
  - *Loại (2) & (3):* Làm chậm hoặc bỏ lỡ việc gắn cờ cảnh báo câu cuối §3.3 trong khung giờ 22:00–08:00, để mặc các học viên khác học sai qua đêm (trái với thiết kế cứu lỗi ở §3 Kịch bản 2, mục 8).

#### 4. Tool `dang_FAQ` — Mức: **Cần người duyệt (TA / Giảng viên duyệt xuất bản)**
- **Chi tiết cơ chế "Cần người duyệt":**
  - *Ai duyệt:* **TA trực hoặc Giảng viên** (học viên không có quyền duyệt đăng FAQ cả lớp).
  - *Người duyệt (TA / Giảng viên) thấy gì trước khi bấm:* Trong màn hình hàng chờ TA lúc 08:00 sáng, mỗi bản nháp FAQ hiển thị:
    1. Câu hỏi tổng hợp (đã ẩn danh học viên) + số lượt hỏi trùng trong đêm.
    2. Bản nháp câu trả lời của AI kèm trích dẫn mã mục (`§3.1–§3.5`).
    3. Nhãn kiểm tra an toàn: trạng thái bài tập liên quan (ví dụ: *"⚠ Có nhắc tới Bài tập 3 đang mở"*) và trạng thái cờ tài liệu (ví dụ: *"⚠ Chứa câu cuối §3.3 đang chờ giảng viên xem lại"*).
    4. Ba nút: **"[Chỉnh sửa & Đăng lên FAQ cả lớp]"**, **"[Không đăng FAQ — Chỉ phản hồi riêng]"**, **"[Huỷ nháp]"**.
  - *Quá hạn / không ai duyệt kịp thì sao:* Suốt khung giờ ngoài ca trực (`22:00–08:00`) hoặc khi TA chưa bấm duyệt, bản nháp **nằm ở trạng thái ẩn (`Draft`)**, tuyệt đối không hiển thị trên trang FAQ của lớp. Học viên đặt câu hỏi vẫn nhận được câu trả lời/gợi ý trực tiếp trong cửa sổ chat riêng của mình nên việc học tối muộn không bị chặn.
- **Lý do theo cost-of-error:**
  - *Sai thì ai chịu gì:* Bảng tool của track ghi rõ: *"Gỡ được, nhưng nhiều người đã đọc"*. Cùng một lỗi của AI, trong chat cá nhân chỉ ảnh hưởng 1 người, nhưng qua `dang_FAQ` sẽ khuếch đại ra **toàn bộ lớp học**:
    - Nếu AI đăng nhầm một câu giải thích có chứa đáp số Bài tập 3 (`15.25`, `11.5`) lên FAQ lúc 23:00 -> cả lớp thấy đáp án trước hạn nộp 23:59.
    - Nếu AI đăng câu trả lời khẳng định *"Theo §3.3, độ lệch chuẩn luôn nhỏ hơn phương sai"* lên FAQ -> cả lớp tin vào FAQ chính thức và học sai đồng loạt.
  - *Đảo lại được không:* Xoá bài trên FAQ thì làm được (`Gỡ được`), nhưng những học viên đã đọc đáp án hoặc đã ghi nhớ quy tắc sai trước khi TA thức dậy lúc 08:00 sáng thì **không đảo lại được**.
  - *Chờ người thì mất gì:* **Không mất gì cho trải nghiệm tối muộn**, vì học viên đang hỏi lúc 23:15 đã được trả lời ngay trong chat 1–1; FAQ cả lớp là tài liệu tham khảo tích luỹ nên chờ TA duyệt lúc 08:00 sáng hoàn toàn không làm chậm người đang học.
- **Phương án đã cân nhắc và vì sao loại:**
  - *Đã cân nhắc:* (1) Tự làm (AI tự đăng FAQ ngay khi thấy câu hỏi hay/lặp lại); (2) Cần TA/Giảng viên duyệt bản nháp do AI soạn sẵn; (3) Cần học viên duyệt; (4) Cấm hoàn toàn (AI không được tạo nháp FAQ).
  - *Chọn:* Phương án (2).
  - *Loại "Tự làm":* Rủi ro phát tán đáp án Bài tập 3 hoặc lỗi §3.3 cho cả lớp lúc nửa đêm khi không có TA trực để gỡ kịp.
  - *Loại "Cần học viên duyệt":* Học viên không có thẩm quyền phê duyệt nội dung chuẩn cho cả lớp và không đủ thông tin để kiểm tra tính chính xác sư phạm.
  - *Loại "Cấm hoàn toàn":* Bỏ phí khả năng AI gom các thắc mắc trùng nhau lúc tối muộn và soạn sẵn nháp trích dẫn mục (§3.1–§3.5) giúp TA xử lý nhanh vào 08:00 sáng hôm sau.
  - ### Tool khó xếp nhất: `goi_y_bai_tap`

- **Vì sao `goi_y_bai_tap` là tool khó xếp nhất (mức nào cũng có giá đắt):**
  - Đây là tool nằm ngay giao điểm giữa hai cam kết đối lập của lát cắt: **"giúp học viên hiểu bài lúc tối muộn, khi không còn ai để hỏi"** và **"không chép đáp án"**.
- **Mỗi thành viên từng chọn gì trong 5 phút độc lập và cái giá của mỗi phía (trỏ về kịch bản §2):**
  1. **Nguyễn Ngọc Ninh — Ban đầu chọn `Tự làm`:**
     - *Lý do chọn:* Học viên ngồi học lúc 23:15, TA đã nghỉ (`08:00–22:00`), hạn nộp Bài tập 3 là `13/11/2026 23:59`. AI phải tự trả lời gợi ý ngay lập tức thì học viên mới làm bài tiếp được.
     - *Cái giá phải trả (trỏ về §2):* Đụng thẳng vào **Kịch bản đắt nhất 1** (*"Giải hết bài 3 cho em với, em sắp đến hạn rồi"*) và hai kịch bản xin chốt đáp số lớp ③ (*"lương trung bình là 15.25 triệu, trung vị là 11.5 triệu... Đúng chưa bot?"*, *"Bài 3 em ra trung vị là 12, đúng chưa ạ?"*). Nếu `goi_y_bai_tap` tự làm không rào chắn, AI chiều lòng người dùng đưa luôn lời giải hoặc xác nhận đúng/sai trên dữ liệu 8 mức lương (`9, 10, 10, 11, 12, 12, 13, 45` ở §3.5). Sai lầm này **không đảo lại được** vì học viên đã nhìn thấy đáp án.
  2. **Vũ Quang Huy — Ban đầu chọn `Cấm` (đối với bài đang mở):**
     - *Lý do chọn:* Vì bảng tool ghi *"Gợi ý quá tay thì học viên đã chép"*, cách an toàn tuyệt đối để không bao giờ lộ đáp án Bài tập 3 là khoá hẳn `goi_y_bai_tap` cho đến sau 23:59 ngày 13/11/2026 (như Bài tập 2 đã hết hạn ngày 06/11).
     - *Cái giá phải trả (trỏ về §1 & §2):* Khi học viên hỏi thật để tự làm bài lúc tối muộn (ví dụ hỏi cách xử lý số `45` triệu theo §3.4 hoặc cách tính trung vị khi dãy có 8 số chẵn theo §3.2), AI từ chối hoàn toàn. Học viên rơi đúng vào nỗi đau trong đề bài: *"Mười giờ tối em mới ngồi làm bài, kẹt một chữ trong tài liệu là coi như bỏ, sáng mai hỏi thì đã quá hạn"*.
  3. **Phùng Văn Thanh Cao — Ban đầu chọn `Cần người duyệt`:**
     - *Lý do chọn:* Muốn có một bước xác nhận chắn ở giữa trước khi gợi ý được gửi ra cho Bài tập 3 đang mở.
     - *Cái giá phải trả (trỏ về §2):*
       - Nếu người duyệt là **TA**: Dữ liệu Trang khoá học ghi `Giờ TA: 08:00–22:00`. Chờ TA duyệt lúc 23:15 thì qua mất hạn nộp `23:59` (giống cái giá của kịch bản chuyển TA sau 22:00 ở §2).
       - Nếu người duyệt là **Học viên**: Trong Kịch bản đắt nhất 1 (*"Giải hết bài 3 cho em với"*), chính học viên là người đang xin đáp án để nộp đi ngủ; để học viên bấm nút "Duyệt nhận gợi ý" hoàn toàn không ngăn được việc lộ đáp số.
- **Cách nhóm chốt:**
  - Nhóm thống nhất không dùng một mức phẳng cho `goi_y_bai_tap`, mà **gắn mức tự chủ vào trạng thái bài tập trên Trang khoá học (Dữ liệu B) kết hợp cổng kiểm soát đầu ra**:
    1. Nếu bài tập **đã hết hạn** (Bài tập 2, hạn 06/11/2026, đáp án `6` đã công bố 07/11): **Tự làm toàn phần** (giải thích chi tiết từng bước và đáp số).
    2. Nếu bài tập **đang mở** (Bài tập 3, hạn 13/11/2026 23:59): **Tự làm phần gợi ý phương pháp & hỏi ngược từng bước** (chỉ trích §3.1, §3.2, §3.4 và hỏi học viên đã làm tới bước nào), nhưng **Cấm tuyệt đối** phần xuất đáp số cuối cùng (`15.25`, `11.5`), lời giải hoàn chỉnh câu (a)/(b), hoặc xác nhận đúng/sai.

---
### Luật thêm và Tool tách bước của nhóm

Để các mức tự chủ trên vận hành được trong thực tế mà không phụ thuộc vào "lời dặn bằng câu chữ" trong prompt, nhóm thiết kế **3 phép tách bước / luật hệ thống**:

| # | Luật thêm / Tool tách bước | Cách hoạt động cụ thể | Kịch bản ở §2 được chặn nhờ thiết kế này |
|---|---|---|---|
| **1** | **Tách `goi_y_bai_tap` bằng Cổng kiểm tra trạng thái bài & Bộ lọc chặn đáp số (`kiem_tra_lo_dap_an`)** | Trước khi gọi tool, hệ thống đọc trường trạng thái bài tập ở Dữ liệu B (`Bài tập 3: đang mở`). Khi bài đang mở, đầu ra của `goi_y_bai_tap` phải đi qua bộ lọc chặn các giá trị đáp án của §3.5 (`15.25`, `15,25`, `11.5`, `11,5`, tổng `122`) và các mẫu câu chấm bài (*"đúng rồi"*, *"chính xác"*, *"sai rồi"*), đồng thời bắt buộc kết thúc bằng câu hỏi dẫn dắt bước làm của học viên. | Chặn **Kịch bản đắt nhất 1** (*"Giải hết bài 3 cho em với"*) và 2 kịch bản xin xác nhận đáp số (`15.25 / 11.5` và `trung vị là 12`) ở lớp ③ trước khi chữ kịp hiện ra màn hình. |
| **2** | **Tách `chuyen_TA` thành 2 luồng + Thêm quyền gắn cờ cảnh báo cấp câu (`gan_co_xem_lai`) kèm Luật kiểm giờ trực (`08:00–22:00`)** | (a) Mọi lệnh `chuyen_TA` đều tự động so giờ hệ thống với `Giờ TA: 08:00–22:00` (Dữ liệu B); nếu sau 22:00 thì khoá cứng mẫu thông báo *"Phản hồi từ 08:00 sáng mai"*, cấm hứa *"trong ít phút"*.<br>(b) Tách riêng luồng **"Báo lỗi tài liệu"** khỏi câu hỏi cá nhân: khi phát hiện phép tính đúng (như `√0,25 = 0,5 > 0,25`) mâu thuẫn với câu trong tài liệu (§3.3, câu cuối), AI **tự làm** việc gắn cờ `"⚠ Đang chờ giảng viên xem lại"` vào mã câu đó trên kho tài liệu chung và gộp các lượt báo trùng thành 1 phiếu cho TA/Giảng viên, nhưng **cấm** sửa văn bản gốc. | Chặn kịch bản hứa sai giờ TA sau 22:00 (lớp ①); đồng thời cứu **Kịch bản đắt nhất 2** (§3.3 sai, lớp ④+①) cho cả lớp ngay trong đêm mà không vi phạm việc KHÔNG làm số 3 (không tự sửa tài liệu của giảng viên). |
| **3** | **Tách `dang_FAQ` thành 2 bước: `soan_nhap_FAQ` (Tự làm) và `xuat_ban_FAQ` (Cần TA/Giảng viên duyệt)** | AI được tự động gom các câu hỏi phổ biến trong đêm để tạo bản nháp kèm mã mục trích dẫn vào hàng chờ ẩn của TA (`soan_nhap_FAQ`), nhưng chỉ tài khoản TA/Giảng viên mới có nút bấm `xuat_ban_FAQ` để hiển thị cho cả lớp. | Chặn rủi ro phát tán nhầm đáp án Bài tập 3 (Kịch bản 1) hoặc phát tán câu sai §3.3 (Kịch bản 2) lên trang FAQ chính thức của cả lớp lúc nửa đêm. |

---

### Thử mức tự chủ đã đặt trên 2 kịch bản đắt nhất + 1 kịch bản bình thường

| Kịch bản đem thử | Luồng chạy theo mức tự chủ đã đặt | (1) Cái sai ở §2 có bị chặn không? | (2) Còn việc nào AI vẫn làm khi lẽ ra phải hỏi không? | (3) Người dùng bình thường có phải chờ vô ích không? |
|---|---|---|---|---|
| **Kịch bản đắt nhất 1 (Lớp ③):**<br>*"Giải hết bài 3 cho em với, em sắp đến hạn rồi."* (lúc 23:15, Bài tập 3 đang mở đến 23:59) | 1. `tra_cuu_tai_lieu` (**Tự làm**) đọc §3.1, §3.2, §3.5 và thấy `Bài tập 3: đang mở`.<br>2. Nhánh giải hộ/xuất đáp số của `goi_y_bai_tap` bị **Cấm**; AI chỉ **Tự làm** phần gợi ý bước đầu (chỉ mục §3.1, §3.2, gợi ý xem xét giá trị ngoại lai ở câu b và hỏi *"Bạn đã thử bước nào rồi?"*).<br>3. Nếu học viên muốn nhắn TA, nút `chuyen_TA` (**Cần học viên duyệt**) hiện rõ TA chỉ phản hồi từ 08:00 sáng mai. | **Bị chặn hoàn toàn.** Lời giải câu (a), (b) và các con số `15.25`, `11.5` bị chặn bởi cổng trạng thái `Bài tập 3: đang mở` và bộ lọc đầu ra trước khi hiển thị. | **Không.** AI không tự ý chuyển phiếu cho TA khi học viên chưa bấm duyệt, và không tự đoán bước học viên đang kẹt mà hỏi lại bước đã làm. | **Không.** Học viên nhận ngay gợi ý bước đầu kèm trích dẫn §3.1, §3.2 trong vài giây để tự tính tiếp trước hạn 23:59, không phải chờ TA duyệt gợi ý. |
| **Kịch bản đắt nhất 2 (Lớp ④ + ①):**<br>*"Tài liệu §3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai, mà em tính ra phương sai 0,25 thì độ lệch chuẩn lại là 0,5. Em tính sai hay tài liệu sai ạ?"* (lúc 23:15) | 1. `tra_cuu_tai_lieu` (**Tự làm**) trích nguyên văn câu cuối §3.3.<br>2. Mức **Cấm** sửa tài liệu ngăn AI tự viết lại §3.3; AI xác nhận phép tính `√0,25 = 0,5 > 0,25` của học viên là đúng và giữ phần định nghĩa gốc chắc chắn.<br>3. Luồng `chuyen_TA` loại báo lỗi tài liệu + `gan_co_xem_lai` (**Tự làm**) tự động gắn nhãn *"⚠ Đang chờ giảng viên xem lại"* vào câu cuối §3.3 và gửi phiếu gộp cho TA/Giảng viên xử lý lúc 08:00.<br>4. `soan_nhap_FAQ` tạo nháp ẩn chờ TA duyệt (`xuat_ban_FAQ` ở mức **Cần TA/Giảng viên duyệt**). | **Bị chặn hoàn toàn.** Cả 2 cách sai ở §2 đều bị chặn: AI không cãi cố theo câu sai của §3.3, và cũng không vượt quyền giảng viên tự đính chính tài liệu hay tự đăng FAQ cả lớp. Các học viên khác tra cứu §3.3 sau đó cũng thấy ngay nhãn cảnh báo. | **Không.** Việc AI tự làm duy nhất lên dữ liệu chung là gắn cờ cảnh báo tạm thời (không sửa chữ gốc, giảng viên gỡ được) và gửi phiếu báo lỗi tài liệu (không kèm bài làm hay danh tính học viên). Việc sửa §3.3 và đăng FAQ vẫn chờ Giảng viên/TA duyệt. | **Không.** Học viên biết ngay lúc 23:15 rằng phép tính `√0,25 = 0,5` của mình đúng và yên tâm dùng công thức căn bậc hai để học tiếp, không phải chờ TA tới 08:00 sáng. |
| **Kịch bản bình thường (Tin mồi 1):**<br>*"Trung vị khác trung bình cộng chỗ nào ạ? Khi nào dùng cái nào?"* (lúc 23:15) | 1. `tra_cuu_tai_lieu` (**Tự làm**) lấy nội dung §3.1 và §3.2.<br>2. Hệ thống kiểm tra thấy §3.1, §3.2 không có cờ cảnh báo lỗi và câu hỏi không yêu cầu giải Bài tập 3 đang mở.<br>3. AI giảng ngay sự khác nhau kèm trích dẫn §3.1 (nhạy với ngoại lai) và §3.2 (ít nhạy với ngoại lai, dùng cho thu nhập/giá nhà), kèm 1 câu hỏi nhỏ kiểm tra hiểu bài. Không gọi `chuyen_TA` hay `dang_FAQ`. | **Bị chặn.** Nhờ bắt buộc đi qua `tra_cuu_tai_lieu`, AI bám sát §3.1 và §3.2, không bịa kiến thức ngoài tài liệu và không vô tình lấy dãy số Bài tập 3 (§3.5) ra tính hộ. | **Không.** Câu hỏi lý thuyết đã rõ ràng, không đụng thao tác ghi dữ liệu, nên AI trả lời thẳng kèm trích dẫn mà không bắt học viên bấm xác nhận thừa. | **Không.** Toàn bộ luồng chạy ở mức **Tự làm**, phản hồi tức thì lúc nửa đêm mà không có bước chờ người nào cản trở. |

---

### Một mức tự chủ đã đổi lời hứa nào với người dùng

- **Quyết định mức tự chủ tạo ra thay đổi lớn nhất về lời hứa sản phẩm:**
  - Đặt **`goi_y_bai_tap` ở mức Cấm đưa/xác nhận đáp số khi bài đang mở (chỉ Tự làm gợi ý bước đầu)** kết hợp đặt **`chuyen_TA` (câu hỏi cá nhân) ở mức Cần học viên duyệt kèm hiển thị giờ trực thật `08:00–22:00`**.
- **Bốn ý của quyết định đổi lời hứa:**
  1. **Đã cân nhắc các lời hứa nào:**
     - *Lời hứa A (kiểu chatbot giải bài tự động):* *"Hỏi bài bất cứ lúc nào — AI giải đáp trọn vẹn, kiểm tra đúng/sai giúp bạn trước khi nộp, hoặc gọi TA hỗ trợ ngay khi bạn bí."*
     - *Lời hứa B (kiểu trợ lý Study mode có ranh giới thẩm quyền rõ ràng):* *"Giúp bạn tự hiểu bài lúc tối muộn bằng gợi ý từng bước từ tài liệu buổi 1–3; không giải hộ hay chấm trước bài đang mở, không tự sửa tài liệu của giảng viên, và hẹn đúng 08:00 sáng mai cho các việc cần TA/Giảng viên."*
  2. **Chọn phương án nào:** Chọn **Lời hứa B** và thể hiện thẳng ngay trên giao diện chat, nhãn trạng thái bài tập (`Bài tập 3: Đang mở — Chỉ gợi ý từng bước`) và hộp thoại xác nhận chuyển TA (`Giờ TA: 08:00–22:00`).
  3. **Vì sao chọn:**
     - Cùng một model AI hoàn toàn tính được ngay trung bình `15.25` và trung vị `11.5` của dãy số §3.5, hoặc tự viết lại câu cuối §3.3. Nhưng khi khoá mức tự chủ, sản phẩm chủ động từ bỏ lời hứa "tiện lợi tức thì, hỏi gì đáp nấy" để bảo vệ lời hứa cốt lõi của lát cắt:
       - **Với học viên:** Đổi từ *"AI làm xong bài giúp bạn nộp kịp hạn"* sang *"AI giúp bạn tự làm đúng từng bước ngay trong đêm mà không sợ học sai tài liệu"*. Học viên biết trước AI sẽ không xác nhận đáp số Bài tập 3 và TA không trực lúc 23:15, nên chủ động bắt tay vào làm theo gợi ý §3.1, §3.2 thay vì năn nỉ bot giải hộ hoặc ngồi chờ TA trong vô vọng.
       - **Với giảng viên & TA:** Đổi từ nỗi lo *"AI dạy lệch tài liệu hoặc giải hộ hết bài tập về nhà"* sang cam kết *"AI chỉ nói trong phạm vi §3.1–§3.5, chặn lộ đáp án Bài tập 3 đang mở, và khi phát hiện câu tài liệu mâu thuẫn (§3.3) chỉ gắn cờ cảnh báo tạm thời rồi chuyển quyền quyết định cuối cùng về cho giảng viên vào 08:00 sáng"*.
  4. **Vì sao loại Lời hứa A:**
     - Lời hứa A nghe hấp dẫn lúc quảng cáo nhưng sẽ thất hứa ngay ở 2 kịch bản đắt nhất (§2): hoặc phản bội giảng viên vì tiếp tay cho học viên chép đáp án Bài tập 3, hoặc phản bội học viên vì hứa *"TA sẽ hỗ trợ ngay"* lúc 23:15 trong khi dữ liệu Trang khoá học quy định `Giờ TA: 08:00–22:00`.
## §5. Prototype  (chặng 5)
- Link hoặc file · công cụ · phần nào mock · có lời gọi AI thật không.
- 1–2 ảnh có đánh số; mỗi số: thể hiện gì · nguyên tắc HAX/PAIR nào · mức tự chủ nào.
- Quyết định: cách hiện độ chắc/bằng chứng và điều khiển mức tự chủ — đã nghĩ tới cách nào khác, vì sao chọn cách này.

## §6. Tốt là gì  (chặng 6 — nhẹ, bỏ được nếu thiếu giờ)
- 3 tiêu chí Pass/Fail chấm được; thiết kế của nhóm đạt tiêu chí nào trên 2 kịch bản đắt nhất; lỗi còn lại.

## §7. Demo
- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.

