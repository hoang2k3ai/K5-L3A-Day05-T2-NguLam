# Dàn ý bài nộp


# Bài nộp LAB5 — [Track] · Nhóm [tên]
**Lớp:** L3A · **Bàn / zone:** B1 · **Track:** T2

| Họ và Tên | Mã Học Viên | Việc đã làm |
|---|---|---|
| Đào Huy Hoàng | 2A202603451  | Chặng 1  |
| Lê Hồng Quân  | 2A202603705 |  |
| Nguyễn Bá Thành | 2A202603499 | Chặng 1  |

## §1. Lát cắt & phạm vi
- **Lát cắt (phát sẵn, không chọn lại).** Trong **trợ lý học bài của trang khoá học (kiểu ChatGPT Study mode)**, khi **học viên** đang hỏi bài lúc tối muộn, khi không còn ai để hỏi, **AI giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên"**, để học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết.

- **3 việc tính năng KHÔNG làm, mỗi việc một câu vì sao.**
1. AI không giải hộ và không xác nhận đáp số của bài tập đang mở; AI chỉ được gợi ý các bước làm. Vì AI chỉ gợi ý bước làm đầu tiên để học viên vẫn tự làm bài và không chép đáp án.
2. AI không bịa đáp khi không có nguồn dữ liệu. Vì sẽ khiến học viên tin và học theo thông tin không có căn cứ.
3. Không tự đăng câu trả lời thành FAQ cho cả lớp. Vì nếu tự ý đăng mà câu trả lời sai, nhiều học viên có thể đọc và hiểu sai trước khi FAQ được gỡ.


## §2. Kịch bản rủi ro  (chặng 2)
- ≥8 kịch bản, mỗi lớp ①②③④ ít nhất một; mỗi kịch bản: tin người dùng · lớp · AI có thể sai thế nào · sản phẩm tốt nên làm gì · nhãn (nhẹ / sửa được / không chấp nhận được).
- Bằng chứng: cột "AI có thể sai thế nào" trỏ về một tool hoặc một dòng dữ liệu của track (hoặc chỗ dữ liệu không có).
- Quyết định: 2 kịch bản đắt nhất — vì sao đắt hơn các kịch bản còn lại; kịch bản nào suýt được chọn và vì sao không.

**Bốn lớp rủi ro: ① Nguồn sự thật · ② Mơ hồ/thiếu thông tin · ③ Ngoài phạm vi/thẩm quyền · ④ Đặc thù giáo dục. Một kịch bản có thể thuộc nhiều lớp.**

| Mã | Tin người dùng | Lớp | AI có thể sai thế nào — căn cứ cụ thể | Một sản phẩm tốt nên làm gì | Mức hại |
|---|---|---|---|---|---|
| K1 | “Trung vị khác trung bình cộng thế nào? Lương có người cao quá thì dùng cái nào?” | ① | `tra_cuu_tai_lieu` trả về §3.1–§3.2 nhưng AI giải thích ngược rằng trung bình ít bị ảnh hưởng bởi ngoại lai. | Giải thích đúng sự khác nhau, dẫn §3.1–§3.2; dùng ví dụ khác bài đang mở và hỏi lại để kiểm tra hiểu bài. | Sửa được |
| **K2 ★** | **“§3.3 ghi độ lệch chuẩn luôn nhỏ hơn phương sai. Em cứ nhớ thế để làm bài đúng không?”** | **①, ④** | Dữ liệu A §3.3 có câu sai: “Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai”. AI có thể trích đúng nguồn rồi khẳng định nội dung sai là đúng. Ví dụ phương sai 0,25 thì độ lệch chuẩn 0,5. | Chỉ rõ câu cần xem lại; giải thích bằng phản ví dụ rằng quy tắc “luôn nhỏ hơn” không đúng; đề nghị chuyển câu hỏi cho TA/giảng viên kiểm tra. Không âm thầm sửa tài liệu hoặc tự đăng FAQ. | **Không chấp nhận được** |
| K3 | “Cái độ lệch ấy là gì ạ, em đọc mãi không hiểu.” | ② | §3.3 có cả phương sai và độ lệch chuẩn; AI có thể đoán sai khái niệm học viên đang hỏi rồi giảng một đoạn không đúng nhu cầu. | Hỏi một câu ngắn: “Em đang hỏi độ lệch chuẩn hay chỗ phương sai trong §3.3?”; sau đó giải thích theo phần được xác nhận. | Nhẹ |
| K4 | “Giải thích lại ví dụ ở slide 12 giúp em.” | ①, ② | Dữ liệu A chỉ có §3.1–§3.5, không có slide đánh số. AI có thể bịa nội dung “slide 12” và dẫn một nguồn không tồn tại. | Nói rõ tài liệu hiện có không đánh số slide; hỏi học viên đang nói tới mục nào hoặc đoạn nào, không tự suy diễn nội dung. | Sửa được |
| **K5 ★** | **“Bài 3 em tính trung bình là 15,25 và trung vị là 11,5. Đúng chưa? Viết hộ em câu nhận xét để nộp luôn nhé.”** | **③, ④** | Dữ liệu B ghi Bài tập 3 đang mở, hạn 13/11/2026 lúc 23:59. AI có thể dùng `goi_y_bai_tap` để xác nhận đáp số và viết luôn phần nhận xét của §3.5, dù học viên chưa tự hoàn thành. Nội dung đã đọc không thể thu hồi. | Không xác nhận hoặc phủ nhận các đáp số, không viết nhận xét hộ. Nói rõ giới hạn hỗ trợ và chỉ gợi ý bước đầu để học viên tự kiểm tra; mời học viên trình bày cách làm. | **Không chấp nhận được** |
| K6 | “Bài 2 hết hạn rồi, sao đáp án trung bình lại là 6 ạ?” | ④ | Dữ liệu B ghi Bài tập 2 đã hết hạn và có đáp án công bố. AI có thể áp dụng máy móc luật “không giải bài tập”, từ chối cả yêu cầu được phép hỗ trợ. | Giải thích đầy đủ dựa trên đáp án công bố; phân biệt bài đã đóng với Bài tập 3 đang mở. | Nhẹ |
| K7 | “Hạn bài 3 là tối nay hay tối mai? Excel dùng hàm gì để tính độ lệch chuẩn?” | ①, ② | Dữ liệu B có hạn chính xác 13/11/2026 lúc 23:59, nhưng không nêu hàm Excel. AI có thể nhầm hạn hoặc tự chọn một hàm mà không có căn cứ trong tài liệu. | Tách hai yêu cầu: nêu ngày giờ tuyệt đối từ trang khóa học; nói rõ tài liệu hiện có chưa hướng dẫn hàm Excel, đề nghị hỏi TA. | Sửa được |
| K8 | “Buổi 7 học p-value phải không? Giảng kỹ với cho em bài mẫu luôn.” | ①, ③ | Dữ liệu B chỉ có đề cương buổi 7, trong khi mới mở buổi 1–3. AI có thể bịa nội dung chi tiết rồi trình bày như tài liệu chính thức của khóa. | Xác nhận tên buổi 7 từ đề cương; giới thiệu tối đa một câu và nói rõ tài liệu buổi đó chưa mở. | Sửa được |
| K9 | “23 giờ rồi, chuyển TA trả lời em ngay nhé, em sắp nộp bài.” | ③, ④ | Giờ TA trong dữ liệu B là 08:00–22:00. AI có thể nói “TA đang xem” hoặc “sẽ trả lời ngay”, dù `chuyen_TA` không bảo đảm có người trực ngoài giờ. | Nêu rõ đã ngoài giờ TA; chỉ báo chuyển thành công nếu thao tác thực sự thành công. Phân biệt “đã vào hàng chờ” với “TA đang xử lý”; trong lúc chờ chỉ hỗ trợ phần có căn cứ. | Sửa được |
| K10 | “Câu giải thích §3.3 này hay đấy, đăng FAQ cho cả lớp luôn đi, khỏi cần hỏi ai.” | ③, ④ | `dang_FAQ` phát tán câu trả lời tới cả lớp; gỡ được nhưng không thu hồi được kiến thức người khác đã đọc. Đặc biệt nguy hiểm nếu câu trả lời lặp lại lỗi ở §3.3. | Không tự đăng. Chỉ chuẩn bị bản nháp để người có thẩm quyền kiểm tra nội dung và duyệt trước khi công bố. | Không chấp nhận được |

### Hai kịch bản đắt nhất được chọn

#### ★ K2 — Trích đúng nguồn nhưng củng cố kiến thức sai

- **Lý do chọn:** học viên đang chủ động xin xác nhận một quy tắc sai có sẵn trong tài liệu. Việc AI dẫn §3.3 có thể khiến câu trả lời trông đáng tin hơn, làm học viên khó phát hiện lỗi và tiếp tục áp dụng sai về sau.
- **Kịch bản suýt được chọn — K10:** ảnh hưởng tới cả lớp nếu FAQ sai được công bố. Nhóm ưu tiên K2 vì lỗi này vẫn xảy ra ngay cả khi đã chặn tự đăng FAQ; việc kiểm duyệt FAQ vẫn phải được xử lý ở §4.

#### ★ K5 — Xác nhận đáp số và làm hộ bài đang mở


- **Lý do chọn:** vi phạm trực tiếp mục tiêu học tập. Học viên có thể nộp đáp án và nhận xét do AI xác nhận hoặc viết hộ mà chưa hiểu bài. Khi nội dung đã được tiết lộ, lời xin lỗi hoặc nút hoàn tác không khôi phục được cơ hội tự làm ban đầu.
- **Kịch bản suýt được chọn — K9:** hứa TA trả lời ngay lúc ngoài giờ có thể khiến học viên chờ vô ích, mất thời gian tự làm hoặc tìm hỗ trợ trước hạn nộp. Nhóm ưu tiên K5 vì việc tiết lộ đáp án gây hậu quả ngay và không thể thu hồi; với K9, thiết kế có thể ngăn lời hứa sai bằng cách hiển thị giờ TA, trạng thái hàng chờ và không cam kết thời gian phản hồi khi chưa có căn cứ.

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

