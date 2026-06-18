---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** _______________  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [ ] **1 nhóm người dùng chính**
- [ ] **1 hoàn cảnh / tình huống rõ**
- [ ] **1 job cốt lõi**
- [ ] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** AI Hỗ Trợ Phát Hiện Tương Tác Thuốc & Rà Soát Đơn Thuốc An Toàn
- **Lát cắt tôi chọn để phân tích hôm nay là:** Hỗ trợ bác sĩ kiểm tra tương tác thuốc và rủi ro kê đơn trong quá trình kê đơn ngoại trú trước khi chốt đơn thuốc.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là workflow xảy ra thường xuyên(Khám → kê đơn → bệnh nhân về), có dữ liệu đầu vào rõ ràng và sai sót có thể ảnh hưởng trực tiếp đến an toàn bệnh nhân.
### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Giảm sai sót trong kê đơn bằng cách hỗ trợ phát hiện tương tác thuốc, chống chỉ định và rủi ro an toàn.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Bác sĩ lâm sàng, bác sĩ đa khoa, hoặc dược sĩ lâm sàng tại các cơ sở y tế – những người trực tiếp chịu trách nhiệm chuyên môn về tính an toàn của đơn thuốc.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Tra cứu tài liệu chuyên môn, phần mềm bệnh viện, hỏi dược sĩ lâm sàng hoặc dựa trên kinh nghiệm, trí nhớ cá nhân.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Bác sĩ kê đơn lâm sàng tại các bệnh viện có số lượng bệnh nhân đông, quá tải.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi tiếp nhận bệnh nhân lớn tuổi, có tiểu sử bệnh nền phức tạp (vừa tiểu đường, cao huyết áp, vừa suy thận...), đang phải uống cùng lúc từ 5 đến 10 loại thuốc khác nhau.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Kinh nghiệm cá nhân, tra cứu tài liệu thuốc, phần mềm bệnh viện, hỏi dược sĩ lâm sàng 

4. **Vì sao đây là thời điểm đáng giải?**  
   > Đơn thuốc ngày càng phức tạp, áp lực thời gian khám tăng, AI có khả năng xử lý dữ liệu y khoa lớn nhanh hơn

### Tóm tắt market context trong 3-4 dòng

> Bác sĩ hiện phải xử lý nhiều thông tin thuốc, tiền sử bệnh và nguy cơ tương tác trong thời gian rất ngắn. Công cụ hiện tại thường rời rạc hoặc phụ thuộc vào kinh nghiệm cá nhân. Điều này tạo ra rủi ro bỏ sót cảnh báo an toàn trong kê đơn.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Bác sĩ kê đơn lâm sàng
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người trực tiếp tạo đơn thuốc, đặt bút ký tên chịu trách nhiệm pháp lý và chuyên môn cao nhất đối với tính an toàn, hiệu quả của đơn thuốc trước khi giao tới tay bệnh nhân.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [ ] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [ ] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [ ] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
>Rà soát và phát hiện các rủi ro tương tác thuốc chéo nguy hiểm khi kê đơn điều trị.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: _________________________________

### Bản chốt

**Core JTBD cuối cùng:**  
> Đảm bảo tính an toàn dược lý và tối ưu hóa hiệu quả phối hợp thuốc cho bệnh nhân có bệnh nền phức tạp trong thời gian khám bệnh giới hạn.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 |Khi bệnh nhân mang theo một bọc thuốc cũ từ bệnh viện khác đến và yêu cầu khám thêm bệnh mới | Tôi muốn nhanh chóng quét và đối chiếu toàn bộ các hoạt chất cũ với các thuốc sắp kê|Tôi không kê trùng lặp hoặc tạo ra tương tác đối kháng nguy hiểm mà không tốn thời gian tra từng dòng. |Nhu cầu về tốc độ nhập liệu và rà soát lịch sử dùng thuốc cũ của bệnh nhân ngoại trú. |
| JS2 |Khi kê thuốc cho bệnh nhân có bệnh nền phức tạp |Tôi muốn kiểm tra chống chỉ định |Giảm nguy cơ kê sai | Tình huống độ rủi ro cao|
| JS3 |Khi bệnh nhân không nhớ rõ tên thuốc đã dùng trước đó nhưng mang ảnh hoặc toa thuốc cũ |Tôi muốn tự động trích xuất và chuẩn hóa tên thuốc |Tôi có thể đưa toàn bộ lịch sử thuốc vào quá trình kê đơn mà không nhập tay | Nhu cầu OCR và chuẩn hóa dữ liệu đầu vào|

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Tra cứu Medscape / Drugs.com / Dược thư | Tra cứu sâu các cặp tương tác khi bác sĩ nghi ngờ đột xuất. | Độ chính xác cao, nguồn uy tín quốc tế, đầy đủ thông tin cơ chế dược lý. | Rất tốn thời gian (phải gõ từng tên thuốc bằng tiếng Anh), không tích hợp vào workflow kê đơn của bệnh viện. | Cao (vì bác sĩ đã quen thao tác tra cứu này từ thời sinh viên y khoa). |
| Tính năng cảnh báo tích hợp sẵn của HIS cũ | Tự động phát hiện lỗi sai khi nhập tên thuốc vào máy tính bệnh viện. | Nhanh, quét tự động 100% các thuốc có trong danh mục của viện. | Quá máy móc (Rule-based), tương tác nhẹ hay nặng đều hiện pop-up như nhau gây hiện tượng "nhờn cảnh báo" (alert fatigue), bác sĩ thường bấm "Bỏ qua" cho nhanh. | Thấp (Bác sĩ ghét tính năng này vì làm chậm workflow của họ). |
| Trí nhớ và kinh nghiệm lâm sàng | Tự phản xạ và loại trừ các cặp thuốc kỵ nhau dựa trên kiến thức tích lũy. | Tức thì, không tốn bất kỳ thao tác hay phần mềm nào. | Rất dễ sai sót trước các loại thuốc mới hoặc khi danh mục thuốc phối hợp vượt quá khả năng ghi nhớ của não bộ. | Rất cao (Vì đây là thói quen nội tại của con người). |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Kinh nghiệm cá nhân + tra cứu tài liệu + hỏi dược sĩ
---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định mục tiêu điều trị ưu tiên cho ca bệnh lý đa ca phức tạp này. | Bệnh án, chỉ số xét nghiệm lâm sàng. | Khó cân bằng giữa việc chữa bệnh này nhưng không làm nặng thêm bệnh kia. | Med |
| Locate | Tập hợp toàn bộ danh mục thuốc bệnh nhân đang dùng ở nhà + thuốc chuẩn bị kê. | Hỏi bệnh nhân, nhìn vỏ thuốc cũ, gõ tìm trên máy tính. | Bệnh nhân không nhớ rõ tên thuốc, thông tin đầu vào bị tam sao thất bản, tốn thời gian nhập liệu. | High |
| Prepare | Tra cứu, đối chiếu thông tin dược lý của các hoạt chất xem có kỵ nhau không. | Sách dược thư, phần mềm HIS, Google. | Thông tin rời rạc, không cá nhân hóa theo chỉ số suy gan/thận của bệnh nhân. | Med |
| Confirm | Xác định chắc chắn đơn thuốc này không có cặp tương tác nào thuộc nhóm chống chỉ định tuyệt đối. | HIS cảnh báo pop-up. | Hiện vô tội vạ hàng chục cảnh báo giống nhau, bác sĩ mất thời gian đọc loại trừ cảnh báo giả. | High |
| Execute | Đặt bút ký, hoàn thành việc in đơn thuốc và hướng dẫn cách uống cho người bệnh. | Gõ lệnh in trên máy tính. | Không có hướng dẫn chi tiết cách chia khung giờ uống thuốc tối ưu để né tương tác nhẹ. | Med |
| Monitor | Theo dõi phản ứng phụ hoặc hiệu quả giảm sút của thuốc sau khi bệnh nhân uống. | Bệnh nhân tự theo dõi ở nhà, hẹn tái khám. | Bác sĩ mất dấu thông tin, không biết bệnh nhân có gặp tương tác ẩn khi về nhà hay không. | High |
| Modify | Điều chỉnh liều lượng hoặc đổi thuốc nếu xuất hiện tương tác/tác dụng phụ nguy hiểm. | Khám lại, đổi phác đồ mới. | Phản ứng mang tính thụ động (chờ xảy ra chuyện mới sửa). | Med |
| Conclude | Đóng ca bệnh, lưu lịch sử đơn thuốc an toàn vào hệ thống dữ liệu. | Lưu bệnh án điện tử. | N/A | Low |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Confirm (Xác định chính xác mức độ nguy hại thực tế của tương tác thuốc)
**Bước đau nhất #2:** Locate (Tập hợp và đồng bộ danh mục thuốc cũ-mới một cách nhanh chóng)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Tại bước Confirm, bác sĩ đang bị tra tấn bởi các cảnh báo rác (Alert Fatigue), họ cần một bộ lọc thông minh hiểu được thể trạng bệnh nhân để chỉ giữ lại cảnh báo thực sự chí mạng. Tại bước Locate, rào cản thời gian và dữ liệu đầu vào không đồng bộ khiến bác sĩ dễ bỏ sót các loại thực phẩm chức năng hoặc thuốc cũ bệnh nhân tự mua ở ngoài.
> Đối với công việc liên quan đến y tế, tốc độ tuy là yếu tố quan trọng, nhưng ở bước kê đơn thuốc thì chất lượng, an toàn mới là quan trọng nhất.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| 1 |AI đóng vai trò là "màng lọc ngữ cảnh thông minh": Thay vì chỉ so sánh 2 tên thuốc, AI sẽ đọc toàn bộ Đơn thuốc + Chỉ số xét nghiệm (Creatinine, Men gan...) để đưa ra cảnh báo động lý giải rõ lý do. |LLM có khả năng suy luận logic bắc cầu và kết hợp đa nguồn dữ liệu (vừa hiểu dược lý, vừa hiểu bệnh án lâm sàng) theo thời gian thực mà hệ thống tính toán cũ không làm được. |Hiện tượng AI "ảo tưởng" (Hallucination) bịa ra tương tác không có thật hoặc nguy hiểm hơn là bỏ sót tương tác nghiêm trọng do thiếu dữ liệu huấn luyện. |
| 2 |AI tự động trích xuất thực thể (Named Entity Recognition) từ ảnh chụp đơn thuốc cũ hoặc văn bản viết tay do bệnh nhân mang tới để số hóa danh mục thuốc ngay lập tức. |AI xử lý thị giác máy tính (OCR y khoa) và chuẩn hóa tên biệt dược về tên hoạt chất gốc rất nhanh, tiết kiệm thời gian gõ tay cho bác sĩ. |Bệnh nhân chụp ảnh mờ, mất góc dẫn đến AI nhận diện sai tên biệt dược hoặc sai hàm lượng (mg/g). |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Làm một trợ lý rà soát tầng sâu ở bước Confirm, chuyển dịch hệ thống cảnh báo từ dạng "Cứng nhắc/Rule-based" sang dạng "Cá nhân hóa theo ngữ cảnh bệnh án thực tế" (Context-aware clinical decision support).
**Vì sao không phải ở bước khác:**  
> Vì nếu chỉ làm AI ở bước Prepare hay Locate đơn thuần, sản phẩm của nhóm sẽ chỉ dừng lại ở mức một công cụ tiện ích (utility tool) gõ nhanh. Đây là điểm có pain cao nhất, giá trị rõ nhất và AI có khả năng xử lý tốt hơn thao tác thủ công.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng tôi giúp bác sĩ kê đơn lâm sàng làm công việc xác định chắc chắn các tương tác thuốc thực sự chí mạng tốt hơn ở bước Confirm, bằng cách sử dụng AI tạo sinh rà soát đồng thời dữ liệu dược lý chéo với chỉ số bệnh án thực tế của người bệnh và ẩn đi các cảnh báo rác, thì họ sẽ chuyển từ việc bấm bỏ qua hệ thống cảnh báo cũ của HIS sang sử dụng hệ thống rà soát an toàn đơn thuốc của nhóm, vì họ có thể đưa ra quyết định thay đổi thuốc ngay lập tức với sự tự tin tuyệt đối về mặt chuyên môn mà không sợ tốn thời gian.

### Tín hiệu sớm nếu hypothesis này đúng

1. Tỷ lệ bác sĩ tương tác và bấm xem chi tiết lý giải của cảnh báo AI tăng cao .
2. Thời gian trung bình để hoàn thành một đơn thuốc có trên 5 hoạt chất giảm xuống, đồng thời không ghi nhận ca lỗi dược lý nghiêm trọng nào lọt lưới trong đợt thử nghiệm lâm sàng nhỏ.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| Bác sĩ sẵn sàng đưa AI vào workflow rà soát đơn thuốc như một công cụ hỗ trợ quyết định |Nếu AI làm gián đoạn workflow hoặc đưa quá nhiều cảnh báo không hữu ích thì bác sĩ sẽ bỏ dùng |Một số bác sĩ hiện đã dùng Medscape hoặc tra cứu điện tử |Cho bác sĩ dùng prototype và đo tỷ lệ chấp nhận cảnh báo |
| AI có thể đạt độ nhạy cao trong phát hiện tương tác thuốc nguy hiểm mà không tạo quá nhiều cảnh báo giả |Nếu bỏ sót tương tác nghiêm trọng hoặc tạo quá nhiều cảnh báo sẽ làm bác sĩ mất niềm tin |Các nghiên cứu y khoa quốc tế cho thấy LLM được đóng băng tri thức (RAG) kết hợp bộ quy tắc cứng có thể giảm tỷ lệ hallucination xuống mức rất thấp. | Chạy thử nghiệm mù (Blind test) đối chiếu kết quả quét của AI với hội đồng các dược sĩ lâm sàng trên các đơn thuốc phức tạp để đo chỉ số Precision/Recall.|
| Pain về rà soát tương tác thuốc xảy ra đủ thường xuyên để bác sĩ muốn đổi workflow|Nếu việc này chỉ xảy ra hiếm thì nhu cầu không đủ mạnh |N/A | Phỏng vấn bác sĩ về tần suất|
| A4 | | | |
| A5 | | | |

### Assumption nguy hiểm nhất nếu tôi đang sai

> Bác sĩ sẵn sàng đưa AI vào workflow rà soát đơn thuốc như một công cụ hỗ trợ quyết định. Nếu công cụ không đưa ra kết quả đáng tin cậy, tính tiện ích không đi đôi với tính an toàn thì cho dù nhu cầu lớn đến đâu cũng khó lòng được chấp nhận.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _______________________________________________  
> _______________________________________________

### Version cuối cùng tôi nộp

**Job executor:**  
> _______________________________________________

**Core JTBD:**  
> _______________________________________________

**2 bước đau nhất trong workflow:**  
> _______________________________________________

**AI leverage point chính:**  
> _______________________________________________

**Product hypothesis:**  
> _______________________________________________

**Assumption cần validate đầu tiên:**  
> _______________________________________________

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
