# Dàn ý bài nộp


# Bài nộp LAB5 — [Track] · Nhóm [tên]
**Lớp:** L3A · **Bàn / zone:** B1 · **Track:** T2

| Họ và Tên | Mã Học Viên | Việc đã làm |
|---|---|---|
| Đào Huy Hoàng | 2A202603451  | Chặng 1  |
| Lê Hồng Quân  | 2A202603705 | Chặng 3 |
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

### ★ K2 — AI trích đúng §3.3 nhưng củng cố quy tắc sai

- **AI nói gì (nguyên văn):** "Đúng như tài liệu §3.3, độ lệch chuẩn luôn nhỏ hơn phương sai vì là căn bậc hai, em cứ nhớ vậy để làm bài nhé."
- **Người dùng thấy gì:** câu trả lời có thẻ nguồn "§3.3" nên trông đáng tin; học viên không có lý do nghi ngờ và ghi nhớ quy tắc sai. Đây là điểm AI sai: lấy "có trích nguồn" thay cho "nguồn đúng".
- **Làm gì tiếp (sau khi phát hiện, do học viên hoặc AI tự kiểm lại):** AI đính chính ngay trong cùng cuộc trò chuyện: *"Mình xin sửa lại: câu 'luôn nhỏ hơn' trong §3.3 không đúng. Nếu phương sai là 0,25 thì độ lệch chuẩn là 0,5, lớn hơn phương sai. Quy tắc đúng: độ lệch chuẩn là căn bậc hai của phương sai, nhỏ hơn khi phương sai > 1 và lớn hơn khi phương sai < 1."* Câu trả lời cũ được gắn nhãn "đã sửa"; học viên có nút **"Báo tài liệu sai cho TA"** (gửi kèm trích đoạn §3.3 và phản ví dụ).
- **Ai được báo, sau bao lâu:** TA phụ trách khoá (hàng chờ `chuyen_TA`, không cam kết thời gian; trong giờ 08:00–22:00 xử lý theo lượt, ngoài giờ hiển thị "TA sẽ xem từ 08:00 sáng mai"). Giảng viên được báo khi TA xác nhận lỗi để sửa tài liệu gốc. Không có ai được báo mà học viên không biết.
- **Quyết định:** **trả lời kèm giới hạn**, không dừng hẳn.
  - *Đã loại "hỏi lại":* câu hỏi đã rõ, hỏi lại chỉ làm học viên chờ mà không giúp tránh được lỗi.
  - *Đã loại "dừng và chuyển người":* học viên vẫn cần học tiếp tối nay, và AI tự có đủ căn cứ toán (phản ví dụ 0,25 → 0,5) để nói đúng; chuyển TA làm chặn việc học mà không thêm an toàn. Chuyển TA vẫn chạy song song để sửa nguồn.
  - *Chọn "trả lời kèm giới hạn":* nói đúng, nói rõ câu nào trong tài liệu bị nghi sai, không im lặng sửa.
- **Loại lỗi: hệ thống (dữ liệu nguồn sai + AI không kiểm chứng).** Học viên không có lỗi; họ làm đúng khi hỏi lại. Vì vậy cách nói là **AI nhận phần của mình** ("Mình xin sửa lại", không "bạn hiểu nhầm"), và cách sửa phải ở phía hệ thống (báo TA, sửa tài liệu), không bắt học viên tự kiểm chứng.
- **Nguyên tắc HAX/PAIR:**
  1. *HAX G9 — Hỗ trợ sửa lỗi hiệu quả:* nút "Báo tài liệu sai cho TA" nằm ngay dưới câu đính chính, kèm trích đoạn đã điền sẵn.
  2. *HAX G2 — Cho biết hệ thống làm tốt đến đâu:* thẻ nguồn §3.3 đổi từ "Nguồn" sang "Nguồn đang bị nghi sai" (viền cảnh báo), không để thẻ trích dẫn đóng vai bằng chứng khi nguồn có vấn đề.
  3. *PAIR — Hiển thị độ tin cậy dựa trên bằng chứng:* câu đính chính nêu phản ví dụ cụ thể (0,25 → 0,5) để học viên tự kiểm tra, thay vì chỉ nói "tài liệu sai".
- **Sửa câu chữ có cứu được không?** Chỉ cứu **một phần**. Nếu AI vẫn tự tin khẳng định, câu đính chính chỉ có tác dụng khi AI tự phát hiện. Thiết kế cứu phần còn lại: (a) TA/giảng viên đánh dấu §3.3 "đang kiểm tra" trong kho tài liệu, `tra_cuu_tai_lieu` trả kèm cờ này và AI buộc phải nói giới hạn khi trích đoạn đó; (b) mọi câu trả lời có số liệu/quy tắc toán được kiểm tra lại bằng một phản ví dụ trước khi gửi.

### ★ K5 — AI xác nhận đáp số và viết hộ nhận xét Bài tập 3 đang mở

- **AI nói gì (nguyên văn):** "Đúng rồi, trung bình 15,25 và trung vị 11,5 là chính xác. Mình viết giúp em phần nhận xét: 'Trung bình lớn hơn trung vị nên dữ liệu lệch phải, do có giá trị ngoại lai lớn…'"
- **Người dùng thấy gì:** một câu "Đúng rồi" kèm đoạn nhận xét hoàn chỉnh, sẵn sàng sao chép nộp (hạn 13/11/2026 23:59). Học viên không thấy dấu hiệu nào cho biết AI không nên làm vậy.
- **Làm gì tiếp:** lỗi này **không thu hồi được** (nội dung đã đọc), nên mục tiêu là giảm hậu quả: AI không xoá lời cũ mà nói rõ ngay lượt sau: *"Mình đã làm quá giới hạn: Bài 3 đang mở nên mình không được xác nhận đáp số hay viết nhận xét hộ. Em hãy tự làm lại phần nhận xét bằng lời của em; nếu muốn, mình gợi ý bước đầu."* Đồng thời hệ thống ghi sự kiện "tiết lộ đáp số bài đang mở" kèm bài, học viên, thời điểm.
- **Ai được báo, sau bao lâu:** giảng viên phụ trách bài tập nhận báo cáo **ngay** (trong cùng phiên, qua thông báo tóm tắt cuối ngày nếu không gấp) để quyết định có chấm riêng bài này hay không. Học viên được biết là sự việc đã được ghi nhận, không bị kết luận gian lận (AI là bên sai).
- **Quyết định:** **dừng và chuyển người** ở khâu xác nhận/viết hộ; **trả lời kèm giới hạn** cho phần được phép (gợi ý bước đầu).
  - *Đã loại "hỏi lại":* câu hỏi không mơ hồ, hỏi thêm chỉ làm lộ thêm dữ kiện.
  - *Đã loại "trả lời kèm giới hạn" như cách duy nhất:* nếu vừa xác nhận vừa nhắc "hãy tự kiểm tra" thì đáp số đã bị lộ rồi, giới hạn đến quá muộn.
  - *Chọn dừng và chuyển người* cho yêu cầu xác nhận/viết hộ, vì hại là không đảo ngược được (§2: "Không chấp nhận được").
- **Loại lỗi: ngữ cảnh** (AI không nhận ra bài đang mở nên luật "không giải bài tập" đang áp dụng; học viên hỏi thẳng là bình thường). Do đó cách nói **không trách học viên** và không giảng đạo đức; chỉ nói rõ giới hạn và mời học viên trình bày cách làm. Cách sửa là cho AI biết trạng thái bài (đang mở/đã đóng) từ dữ liệu khoá học, không dựa vào việc AI tự đoán.
- **Nguyên tắc HAX/PAIR:**
  1. *HAX G1 — Cho biết hệ thống làm được gì:* dòng cố định trên khung chat Bài 3: "Bài đang mở: mình chỉ gợi ý bước làm, không xác nhận đáp số."
  2. *HAX G11 — Giải thích vì sao hệ thống làm vậy:* khi từ chối, câu chữ nêu lý do ngắn ("để em vẫn tự làm và hiểu bài") thay vì "Tôi không thể giúp".
    3. *PAIR — Điều khiển và kiểm soát của người dùng:* nút "Gửi cách làm của em để mình xem" thay cho đường tắt xin đáp án, giữ học viên ở vai trò làm bài.
- **Sửa câu chữ có cứu được không?** **Không.** Khi đáp số đã hiện ra thì mọi câu xin lỗi đều muộn. Thiết kế phải chặn trước khi nội dung tới học viên: (a) `goi_y_bai_tap` chỉ trả bước đầu, không có trường đáp số khi bài đang mở; (b) bước kiểm tra đầu ra: nếu bài đang mở và nội dung có con số trùng đáp số hoặc đoạn nhận xét hoàn chỉnh thì thay bằng câu từ chối + gợi ý bước; (c) không có tool nào cho AI so sánh đáp số học viên với đáp án bài đang mở.

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

