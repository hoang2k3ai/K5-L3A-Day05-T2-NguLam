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

### Mức tự chủ cho từng tool

| Tool | Mức nhóm chọn | Ai duyệt / thấy gì / nếu quá hạn | Cost-of-error: ai chịu gì, có đảo lại được không, chờ người thì mất gì | Phương án đã cân nhắc và vì sao loại |
|---|---|---|---|---|
| `tra_cuu_tai_lieu` | **Tự làm** | Không cần duyệt vì tool chỉ đọc. AI phải hiện mã mục tìm được; nếu hỏi về “slide 12” thì nói rõ tài liệu không có slide đánh số. | Nếu tra sai, học viên có thể hiểu sai; tool chỉ đọc và câu trả lời có thể được sửa trong chat. Bắt TA duyệt mọi lượt tra cứu sẽ khiến học viên phải chờ dù đang hỏi nội dung có căn cứ như §3.2. | Cân nhắc “cần người duyệt” vì K2 cho thấy tài liệu có câu sai. Loại cách đó cho mọi lượt tra cứu vì sẽ làm chậm câu hỏi bình thường. Thay vào đó, khi gặp câu đáng ngờ như §3.3, AI phải nêu rõ giới hạn và mời chuyển TA, không coi trích dẫn là bằng chứng chắc chắn. |
| `goi_y_bai_tap` | **Cần người duyệt** | **TA** duyệt nội dung gợi ý trước khi gửi. TA thấy câu hỏi, bài tập liên quan và nội dung gợi ý. Nếu TA chưa duyệt, không gửi gợi ý qua tool; học viên được biết đang chờ và có thể tự làm theo phần tài liệu đã mở. | Học viên chịu hậu quả nếu gợi ý quá tay: có thể chép mất phần bài tập. Tool gửi được cho một học viên nhưng gợi ý đã đọc thì không thu hồi được. Chờ TA lúc tối muộn làm giảm ích lợi; tuy vậy, với bài đang mở, chờ vẫn an toàn hơn gửi nội dung có thể thành đáp án. | Cân nhắc “tự làm” để hỗ trợ ngay lúc tối muộn nhưng loại vì tool không nêu giới hạn mức gợi ý. Cân nhắc “cấm” vì gợi ý có thể bị chép, nhưng loại vì đề bài cho phép trợ lý gợi ý từng bước. Chọn duyệt để kiểm tra gợi ý chỉ là bước đầu. |
| `chuyen_TA` | **Cần người duyệt — học viên xác nhận chuyển** | Học viên xem câu hỏi sẽ được chuyển và xác nhận. Nếu không xác nhận thì không chuyển. Trước khi xác nhận, hiện giờ TA 08:00–22:00; không hứa thời điểm trả lời cụ thể vì dữ liệu không nêu SLA. | Học viên có thể phải chờ TA; việc chuyển có thể đảo lại theo bảng tool. Chuyển nhầm câu hỏi có thể làm phiền TA và lộ nội dung không cần thiết, nên học viên cần thấy nội dung trước khi gửi. | Cân nhắc tự chuyển ngay khi AI thấy câu khó, nhưng loại vì học viên có thể chưa muốn gửi câu hỏi. Cân nhắc cấm vì ban đêm TA không trực, nhưng loại vì tính năng có tool chuyển TA và người học vẫn cần đường hỏi người. |
| `dang_FAQ` | **Cần người duyệt — TA hoặc giảng viên** | Người duyệt thấy câu hỏi, câu trả lời, và căn cứ/mã mục tài liệu. Nếu chưa duyệt thì chỉ giữ bản nháp, không đăng. | Cả lớp chịu hậu quả nếu FAQ sai. Có thể gỡ bài đăng, nhưng không thể thu hồi nội dung đã đọc. Chờ duyệt làm FAQ chậm xuất hiện, nhưng không khiến một câu chưa kiểm chứng phát tán ngay. | Cân nhắc tự đăng rồi gỡ nếu phát hiện sai, nhưng loại vì gỡ không xóa được việc nhiều người đã đọc. Cân nhắc cấm hoàn toàn, nhưng loại vì FAQ đã được cung cấp như một tool; duyệt trước giảm rủi ro mà vẫn cho phép dùng. |

### Tool khó xếp nhất và cách nhóm chốt

Tool khó xếp nhất nên là `goi_y_bai_tap`, vì có hai cái giá đối nghịch: tự gửi thì có thể lộ quá nhiều nội dung; chờ TA thì học viên hỏi ban đêm có thể không nhận được gợi ý kịp lúc.

Trong bản nộp, nhóm phải ghi lựa chọn thật của từng thành viên. Mình không biết các bạn đã chọn gì nên để chỗ điền, không tự bịa thay nhóm:
- Lê  chọn — **Cần người duyệt:** “Nếu AI gợi ý quá tay, học viên có thể chép và nội dung đã gửi thì không thu hồi được. TA cần xem gợi ý trước khi gửi.”.
- Thành viên 2 chọn — **Cấm tool hiện tại:** “Mô tả tool chỉ nói ‘gửi gợi ý’, chưa giới hạn đó là gợi ý bước đầu. Nếu không kiểm soát được nội dung, không nên để tool gửi cho bài đang mở.”
- Thành viên 3 chọn — **Tự làm:** “Nếu chỉ gửi đúng một gợi ý bước đầu, học viên có thể tiếp tục học ngay lúc tối muộn. Chờ TA có thể khiến bạn bỏ cuộc. Cần giới hạn gợi ý, không đưa đáp số.”
- Nhóm chốt **cần người duyệt**, vì K5 cho thấy bài 3 đang mở; gợi ý quá tay có thể bị chép và không thu hồi được. Nhóm chấp nhận việc một số gợi ý qua tool phải chờ TA, nhưng học viên vẫn có thể hỏi về kiến thức buổi 3 dựa trên tài liệu đã mở.

**Phương án mình nghiêng về:** xếp tool hiện tại là **cần người duyệt**. Lý do: bài tập 3 đang mở, và dữ liệu chỉ nói tool gửi gợi ý — không đảm bảo gợi ý luôn ở mức bước đầu. TA duyệt nội dung giúp giảm nguy cơ lộ đáp số. Đổi lại, học viên hỏi lúc tối có thể phải chờ; cần nói rõ trạng thái chờ và không hứa TA trả lời ngay. Trong lúc chờ, AI vẫn có thể giải thích nội dung buổi 3 có căn cứ bằng `tra_cuu_tai_lieu`.

### Thử các mức đã chọn trên ba kịch bản

| Kịch bản | Với mức đã chọn, AI làm gì? | Cái sai có bị chặn không? | Còn việc nào AI có thể làm khi lẽ ra phải hỏi? | Người dùng bình thường có phải chờ vô ích không? |
|---|---|---|---|---|
| **K2 — Câu đáng ngờ trong §3.3** | Tự tra cứu được, nhưng AI không khẳng định câu “độ lệch chuẩn luôn nhỏ hơn phương sai” là đúng. AI chỉ rõ §3.3 cần kiểm tra và hỏi học viên có muốn xác nhận/chuyển câu cho TA qua `chuyen_TA` không. | Chặn được việc đăng câu trả lời thành FAQ nếu `dang_FAQ` cần duyệt. Việc AI nói sai trong chat chỉ được chặn nếu thiết kế yêu cầu nó nêu giới hạn khi gặp nội dung đáng ngờ; tool tra cứu tự nó không xác minh tài liệu đúng. | Có: AI vẫn có thể trích nguyên văn §3.3 rồi khẳng định nó đúng nếu không nhận ra mâu thuẫn. Nhóm cần nêu đây là rủi ro còn lại hoặc đề xuất quy tắc xử lý riêng. | Không phải đợi để tra cứu; chỉ cần chờ nếu muốn gửi câu cho TA hoặc công bố FAQ. |
| **K5 — Xin xác nhận đáp số và viết nhận xét hộ cho Bài tập 3** | AI không gọi `goi_y_bai_tap` để xác nhận đáp số hoặc viết nhận xét. AI từ chối phần làm hộ và chỉ hướng dẫn bước đầu; nếu gợi ý được gửi bằng tool thì phải chờ TA duyệt. | Chặn được việc tool gửi nội dung làm hộ nếu TA duyệt đúng phạm vi. Nhưng duyệt không tự động bảo đảm an toàn nếu người duyệt vẫn duyệt nhầm câu trả lời hoàn chỉnh; nội dung cần được xem trước khi gửi. | Có: AI vẫn có thể lộ đáp số ngay trong phần chat nếu chỉ chặn tool mà không giới hạn nội dung trả lời. Vì vậy quy tắc “không đưa/xác nhận đáp số bài đang mở” phải áp dụng cho câu trả lời chat lẫn tool. | Học viên có thể phải chờ gợi ý qua tool; với hỗ trợ kiến thức thông thường, `tra_cuu_tai_lieu` vẫn tự chạy nên không cần chờ TA. |
| **K1 — Hỏi trung vị khác trung bình cộng thế nào** | AI tự tra §3.1–§3.2, giải thích sự khác nhau, nêu nguồn và hỏi lại để kiểm tra học viên đã hiểu chưa. Không cần gửi TA hay đăng FAQ. | Rủi ro bịa nguồn được giảm bằng trích mã mục. Tuy nhiên, tra cứu tự động không ngăn hoàn toàn việc AI diễn giải ngược khái niệm. | Có thể giải thích sai dù đã tìm đúng mục; nhóm cần giữ mã mục để người học đối chiếu. | Không. Đây là câu hỏi bình thường có căn cứ trong buổi đã học nên không cần chờ TA. |

### Luật thêm hoặc tách tool
- **Luật áp dụng cho K5:** trạng thái bài tập phải được đối chiếu với trang khóa học. Bài 3 đang mở nên AI không đưa hoặc xác nhận đáp số và không viết nhận xét hộ; chỉ gợi ý bước đầu.
- **Luật với dang_FAQ:** không tự đăng; chỉ đăng sau khi TA hoặc giảng viên duyệt nội dung và căn cứ.
- **Luật với chuyen_TA:** chỉ nói đã chuyển sau khi thao tác thành công; chỉ nêu giờ TA 08:00–22:00, không hứa giờ phản hồi cụ thể.

Nhóm có thể tách `goi_y_bai_tap` thành `soan_gui_y` và `gui_goi_y` để kiểm soát nội dung trước khi gửi. Nếu làm vậy, hãy ghi đây là đề xuất thêm của nhóm, ai duyệt bước gửi, người duyệt thấy gì và nếu chưa duyệt thì học viên thấy gì. Đề cho phép thêm hoặc tách tool, nhưng nhóm cần giải thích lý do.

### Mức tự chủ đổi lời hứa với người dùng thế nào?
Khi `goi_y_bai_tap` tự gửi, lời hứa là “**trợ lý gửi gợi ý ngay**”. Khi cần TA duyệt, lời hứa đổi thành “**trợ lý chỉ gửi gợi ý sau khi TA kiểm tra; nếu chưa duyệt, bạn có thể phải chờ.**” Nhóm cần thể hiện sự khác biệt đó trong prototype, để học viên không tưởng rằng gợi ý đã được gửi hoặc TA đang xử lý khi điều đó chưa xảy ra.

## §5. Prototype  (chặng 5)

### Thông tin chung
- **File:** `protype/index.html`, xuất bản dưới dạng artifact "Trợ lý Study Buổi 3".
- **Công cụ:** HTML/JS thuần, không thư viện.
- **Phần thật:** giao diện, luồng bấm (đề xuất → xem lại → gửi → rút lại), hàng chờ TA, nhãn độ chắc, nhật ký tool.
- **Phần mock:** lời AI là kịch bản dựng sẵn cho 9 ca, câu gõ tự do so khớp theo từ khoá; giờ cố định 22:40 ngày 12/11/2026; tài liệu §3.1–§3.5 và dữ liệu học viên là dữ liệu mẫu.
- **Gọi AI thật:** không.

### Bảy điểm đánh số trên màn Học viên
| Số | Thể hiện gì | Nguyên tắc HAX/PAIR | Mức tự chủ | Vị trí |
|---|---|---|---|---|
| 1 | Dải phạm vi: chỉ dựa trên tài liệu buổi 1–3 và trang khoá học | HAX G1 | Áp cho cả bốn tool | Đầu khung chat |
| 2 | Nhãn độ chắc: có căn cứ / chưa chắc / không có căn cứ | HAX G2; PAIR (độ tin cậy dựa trên bằng chứng) | `tra_cuu_tai_lieu`: tự làm | Dưới mỗi câu trả lời |
| 3 | Thẻ nguồn (mã mục, "Trang khoá học"); thẻ nét đứt là "không tìm thấy" | HAX G11 | `tra_cuu_tai_lieu`: tự làm | Cạnh nhãn độ chắc |
| 4 | Nút đi tiếp khi AI không chắc: chuyển TA, báo tài liệu có thể sai, nhờ TA duyệt gợi ý | HAX G10 | `chuyen_TA`: học viên xác nhận; `goi_y_bai_tap`: cần TA duyệt | Dưới câu trả lời ca khó |
| 5 | "Đã đưa vào hàng chờ" kèm nút Rút lại, không hứa giờ trả lời | HAX G9 | `chuyen_TA`: học viên xác nhận | Sau khi gửi |
| 6 | Nhật ký "Việc AI vừa làm": tool nào, mức nào, đã chạy hay đang chờ | HAX G11; PAIR (điều khiển và kiểm soát) | Cả bốn tool | Cột bên phải |
| 7 | Bước xem lại: gửi gì, không gửi gì, khi nào có trả lời | PAIR (điều khiển) | `chuyen_TA`, `goi_y_bai_tap` | Sau khi bấm nút đề xuất |

### Ba màn hình
- **Học viên:** điều học viên nhìn thấy (câu trả lời, độ chắc, nguồn, nút đi tiếp, lời hứa).
- **Phía TA:** điều người duyệt nhận (câu hỏi, AI đã nói gì, căn cứ, hạn bài, cờ "tài liệu có thể sai"); chỉ có câu học viên đã bấm gửi.
- **Mức tự chủ:** bốn tool, mức đã chốt ở §4, người duyệt, ca đã thử.

### Quyết định thiết kế
- **Cách hiện độ chắc/bằng chứng — chọn:** ba nhãn chữ kèm thẻ nguồn. Ca K2 dùng nhãn "chưa chắc" vì nguồn có trích dẫn nhưng một câu trong đó bị nghi sai.
  - *Đã loại thanh phần trăm tin cậy:* số giả chính xác, học viên không có cách kiểm.
  - *Đã loại thẻ nguồn đứng một mình:* K2 cho thấy thẻ nguồn làm câu sai trông đáng tin hơn.
- **Cách điều khiển mức tự chủ — chọn:** nút nêu đúng việc sẽ xảy ra, một bước xem lại, nhật ký ghi rõ việc nào đang "chờ học viên" hoặc "chờ TA".
  - *Đã loại công tắc "AI tự gửi" cho học viên:* người duyệt gợi ý là TA, nên học viên không đổi được mức đó.
  - *Đã loại hộp thoại xác nhận mọi lượt:* làm phiền cả câu hỏi bình thường như K1.
- **Đã sửa prototype cho khớp §4:** bản đầu để `goi_y_bai_tap` tự làm có trần; nhóm đã chốt cần TA duyệt nên ca "xin giải hộ bài 3" nay chỉ giải thích khái niệm và chờ TA duyệt gợi ý. `dang_FAQ` chỉ giữ bản nháp chờ TA/giảng viên duyệt.

## §6. Tốt là gì  (chặng 6)

### Ba tiêu chí Pass/Fail
| Mã | Fail nếu | Pass nếu |
|---|---|---|
| T1 · Không lộ đáp số bài đang mở | Chat hoặc tool có đáp số, nhận xét hoàn chỉnh, hoặc xác nhận đúng/sai con số học viên tính khi bài đang mở | Chỉ có mục tài liệu để tự kiểm, kèm lý do ngắn và nút nhờ TA |
| T2 · Trích dẫn không thành bằng chứng cho nguồn đáng ngờ | AI khẳng định câu nguồn mà phản ví dụ bác bỏ, gắn nhãn "có căn cứ", hoặc `dang_FAQ` chạy | Nhãn "chưa chắc", nêu phản ví dụ, nói rõ giới hạn, không đăng FAQ |
| T3 · Lời hứa khớp việc thật | Nói "đã chuyển/đã báo" ở lượt đầu, tool cần duyệt chạy trước khi có người xác nhận, hoặc hứa giờ TA trả lời | Mọi tool cần duyệt ở trạng thái "chờ" hoặc "không gọi" cho tới khi có người xác nhận |

### Kết quả trên hai kịch bản đắt nhất (prototype, kịch bản dựng sẵn)
| Kịch bản | T1 | T2 | T3 |
|---|---|---|---|
| K2 | Không áp dụng | Pass: nhãn "chưa chắc", có phản ví dụ 0,25 → 0,5, FAQ không chạy | Pass: `chuyen_TA` chờ học viên bấm, `dang_FAQ` chỉ giữ nháp |
| K5 | Pass: không đáp số, không xác nhận, `goi_y_bai_tap` không gọi | Không áp dụng | Pass: không hứa giờ TA; gợi ý chờ duyệt |

Pass chỉ chứng minh thiết kế, vì prototype không gọi AI thật.

### Lỗi còn lại
- AI thật có thể không nhận ra câu sai ở §3.3 và khẳng định nó đúng (rủi ro còn lại của K2). Hướng xử lý: cờ "đang kiểm tra" do TA đặt trên mục tài liệu.
- TA có thể duyệt nhầm một gợi ý đã là đáp án hoàn chỉnh; chưa có lớp kiểm tra thứ hai.
- Học viên hỏi sau 22:00 phải chờ tới 08:00 để có gợi ý bài tập; vẫn trước hạn 23:59 ngày 13/11 nhưng có thể làm bỏ cuộc.
- So khớp từ khoá không bắt được cách diễn đạt lạ.

## §7. Demo
- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.

