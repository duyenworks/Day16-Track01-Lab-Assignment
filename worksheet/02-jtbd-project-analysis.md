---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** ShopReply — trợ lý phản hồi inbox cho shop online

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

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** ShopReply — công cụ hỗ trợ chủ shop online quản lý và trả lời tin nhắn khách trên Shopee / TikTok Shop
- **Lát cắt tôi chọn để phân tích hôm nay là:** Chủ shop (1–3 người) trả lời câu hỏi **trước khi mua** trong **giờ cao điểm** (19h–23h), khi inbox đổ dồn và không kịp trả lời từng tin
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là pain nhóm nghe nhiều nhất khi phỏng vấn 3 chủ shop nhỏ. Không viết quá rộng kiểu "AI cho e-commerce" — có hoàn cảnh, có workflow, và có thể vẽ job map cụ thể.

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
   > Chủ shop online mất đơn vì trả lời inbox chậm hoặc không nhất quán — đặc biệt lúc inbox tăng đột biến buổi tối.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Chủ shop hoặc nhân viên CSKH kiêm nhiệm (1–3 người), bán trên Shopee / TikTok Shop, doanh thu khoảng 50–500 triệu/tháng.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Trả lời thủ công trên app sàn, copy mẫu câu trong Notes, hoặc nhờ ChatGPT soạn nháp rồi paste lại — mỗi cách đều tốn thời gian và dễ sai thông tin sản phẩm.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Chủ shop online nhỏ và vừa — tự vận hành hoặc có 1–2 người hỗ trợ, không có team CSKH chuyên trách.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi khách nhắn hỏi size, giá ship, hàng còn không, khuyến mãi — ngay trước khi bấm mua. Đỉnh điểm 19h–23h khi chủ shop vừa đóng gói vừa trả lời tin.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Trả lời tay trên app sàn, mẫu câu cố định trong Notes/Zalo, ChatGPT soạn nháp, hoặc thuê thêm người part-time giờ cao điểm.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Sàn thương mại điện tử đo response rate và ảnh hưởng xếp hạng shop. AI đủ tốt để draft câu trả lời, nhưng generic AI không biết tồn kho, policy đổi trả, hay giọng thương hiệu của từng shop — khoảng trống nằm ở đó.

### Tóm tắt market context trong 3-4 dòng

> Hàng triệu shop online ở VN phụ thuộc inbox để chốt đơn, nhưng đa số không có CSKH chuyên nghiệp. Giờ cao điểm tối là lúc vừa mất đơn vừa trả lời sai nếu dùng mẫu câu chung chung. ChatGPT giúp viết nhanh nhưng không có context sản phẩm — đây là lý do có chỗ cho giải pháp gắn workflow shop, không chỉ là chatbot viết văn.

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

- **Job executor của dự án này là:** Chủ shop online (hoặc nhân viên kiêm nhiệm) — người trực tiếp mở app sàn và gõ câu trả lời cho khách
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người đọc tin, quyết định nội dung trả lời, và bấm gửi — không phải đối tác vận chuyển hay nhà cung cấp. Nếu tool không tiết kiệm được thời gian gõ và giảm lo lắng trả lời sai, họ không dùng.

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

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Trả lời inbox khách hàng bằng AI nhanh trong giờ cao điểm

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: AI, inbox (có thể thay bằng "câu hỏi trước mua")

### Bản chốt

**Core JTBD cuối cùng:**  
> Giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm

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
| JS1 | Inbox tăng đột ngột lúc 21h, đang đóng gói hàng | Trả lời từng khách trong vài phút, không bỏ sót tin | Không mất đơn vì phản hồi chậm quá 5 phút | Product cần xuất hiện khi volume cao, không chỉ lúc rảnh |
| JS2 | Khách hỏi size + ship tỉnh xa, tôi không nhớ chính sách | Có câu trả lời đúng policy và tồn kho size đó | Tránh hứa sai rồi phải xin lỗi / đổi trả | Cần context sản phẩm, không chỉ viết hay |
| JS3 | Khách so sánh giá với shop khác, hỏi có giảm thêm không | Phản hồi đúng tone thương hiệu, không hứa lung tung | Giữ margin và uy tín shop | Cần guardrail policy, không chỉ generate tự do |

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

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Alt 1: Trả lời tay trên app Shopee/TikTok | Kiểm soát 100% nội dung gửi đi | Chính xác nếu chủ shop nhớ hết thông tin | Chậm, không scale khi 20+ tin cùng lúc | Thấp — đang là default |
| Alt 2: Mẫu câu trong Notes / Zalo | Trả lời nhanh câu hỏi lặp lại | Nhanh cho FAQ cố định | Sai context (size, màu, tồn kho), giọng máy móc | Thấp |
| Alt 3: ChatGPT soạn nháp → paste | Viết câu trả lời mượt hơn | Nhanh, miễn phí/rẻ, đủ tốt về văn phong | Không biết tồn kho, policy shop; phải copy-paste qua lại | Thấp |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Trả lời tay kết hợp mẫu câu Notes — hoặc ChatGPT nếu họ đã quen workflow copy-paste. Cả hai đều switching cost thấp.

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
| Define | Xác định tin nào cần ưu tiên trả trước | Lướt inbox thủ công, ưu tiên tin mới nhất | Bỏ sót tin cũ chưa đọc; không phân loại theo intent | Med |
| Locate | Tìm thông tin để trả lời (giá, size, ship, tồn) | Nhớ trong đầu, hoặc mở tab sản phẩm / Excel tồn kho | Mất 1–3 phút/tin; hay trả sai size hoặc giá ship | **High** |
| Prepare | Soạn nội dung câu trả lời | Gõ tay hoặc copy mẫu / ChatGPT | Mẫu câu generic; ChatGPT thiếu context shop | **High** |
| Confirm | Kiểm tra trước khi gửi — đúng policy, đúng tone | Đọc lại bằng mắt, đôi khi bỏ qua vì vội | Gửi nhầm khi vội; không có checklist policy | Med |
| Execute | Gửi tin trên app sàn | Bấm gửi trên Shopee/TikTok Shop | N/A — bước này đơn giản | Low |
| Monitor | Theo dõi khách có phản hồi tiếp không | Quay lại inbox sau vài phút | Khó theo dõi khi nhiều thread mở | Med |
| Modify | Sửa câu trả lời nếu khách hỏi thêm | Gõ lại hoặc gọi điện | Tốn thời gian lặp lại Locate + Prepare | Med |
| Conclude | Chốt đơn hoặc kết thúc hội thoại | Nhắc khách đặt hàng, gửi link | Không có follow-up nhất quán | Low |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate — tìm thông tin sản phẩm / policy để trả lời đúng  
**Bước đau nhất #2:** Prepare — soạn câu trả lời nhanh mà vẫn đúng context shop

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là nơi user mất nhiều thời gian nhất mỗi tin (2–5 phút) và cũng là nơi sai sót gây mất đơn / đổi trả. ChatGPT chỉ giải được một nửa (Prepare) mà không có Locate. AI của nhóm chỉ đáng giá nếu gộp cả hai bước với dữ liệu shop thật.

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
| Locate + Prepare | Đọc câu hỏi khách → tra catalog / policy shop → draft câu trả lời có nguồn | LLM giỏi hiểu intent + tổng hợp; khi gắn data shop thì vượt ChatGPT generic | Hallucinate tồn kho / giá; khách tức nếu sai |
| Confirm | Highlight chỗ cần chủ shop duyệt (giảm giá, hứa ship) trước khi gửi | Giảm rủi ro gửi nhầm khi vội; human-in-the-loop phù hợp policy | Nếu friction duyệt quá nhiều, user bỏ qua và mất giá trị |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước **Locate + Prepare**: từ câu hỏi khách → draft trả lời dựa trên catalog, policy ship/đổi trả, và tone shop — chủ shop chỉ review rồi gửi.

**Vì sao không phải ở bước khác:**  
> Execute (gửi tin) đã đủ nhanh trên app sàn. Define (ưu tiên tin) có thể hữu ích nhưng không phải pain lớn nhất. Nếu chỉ làm Prepare mà không có Locate, product trùng ChatGPT — đúng cảnh báo từ Lab 1 (Grammarly / wrapper trap).

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

> Nếu chúng ta giúp **chủ shop online** giải quyết câu hỏi trước mua **nhanh và chính xác hơn ở bước Locate + Prepare**, bằng cách **draft câu trả lời từ catalog và policy shop kèm bước duyệt nhanh**, thì họ sẽ chuyển từ **ChatGPT + mẫu câu Notes** sang **ShopReply**, vì **tiết kiệm 2–3 phút/tin và giảm trả lời sai tồn kho / policy trong giờ cao điểm**.

### Tín hiệu sớm nếu hypothesis này đúng

1. Chủ shop dùng draft của ShopReply ≥ 60% số tin trong giờ cao điểm (chỉ sửa nhẹ, không viết lại từ đầu)
2. Thời gian trung bình trả lời một tin giảm từ ~4 phút xuống dưới 90 giây sau 2 tuần dùng thử

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
| A1: Chủ shop là executor đúng, không phải agency CSKH thuê ngoài | Shop lớn hơn có thể outsource — product khác hẳn | 3 phỏng vấn shop nhỏ; đều tự trả lời | Hỏi thêm 5 shop doanh thu > 500M/tháng xem ai làm job |
| A2: Pain "giờ cao điểm" đủ đau để trả tiền | Có thể chấp nhận mất vài đơn, không muốn trả subscription | 2/3 người phỏng vấn nói từng mất đơn vì trả chậm | Log thời gian trả lời + số tin bỏ sót trong 1 tuần thử |
| A3: User sẽ bỏ ChatGPT nếu có context shop | ChatGPT free, switching cost thấp | Chưa có — chỉ giả định | A/B: draft ChatGPT vs ShopReply, đo tỷ lệ gửi không sửa |
| A4: AI giải tốt Locate + Prepare khi có catalog | Catalog shop hay không chuẩn, thiếu field | Chưa test với data thật | Prototype với 1 shop: import 20 SKU, đo accuracy 20 câu hỏi mẫu |
| A5: Chủ shop tin draft đủ để gửi sau review ngắn | Sợ sai → vẫn viết lại từ đầu | Chưa có | Theo dõi % tin gửi nguyên draft vs viết lại hoàn toàn |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A4** — nếu catalog/policy shop không đủ sạch để AI tra cứu chính xác, toàn bộ moat "context shop" sụp và product chỉ còn là ChatGPT có UI đẹp hơn.

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
| "Shopee có thể tự làm AI inbox — các bạn build trên đất thuê" | Platform risk (từ Lab 1) | Giữ leverage point nhưng thêm moat: policy + tone + multi-platform |
| "ChatGPT + upload file catalog cũng làm được Locate" | AI leverage point | Giữ — nhưng product phải giảm friction upload và duyệt, không chỉ generate |
| "Có chắc chủ shop trả tiền không, hay chỉ dùng free?" | Assumption A2 | Giữ executor; validate willingness-to-pay bằng landing + pre-order |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Phản biện về platform risk làm nhóm chú ý hơn đến multi-platform (Shopee + TikTok Shop) và lưu policy shop riêng — nhưng không đổi job executor hay core JTBD vì 3 phỏng vấn đều khớp. Chỉ bổ sung vào roadmap: nếu chỉ làm Prepare mà không có Locate, product không khác ChatGPT.

### Version cuối cùng tôi nộp

**Job executor:**  
> Chủ shop online (hoặc nhân viên kiêm nhiệm) — người trực tiếp đọc tin và gửi câu trả lời trên app sàn

**Core JTBD:**  
> Giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm

**2 bước đau nhất trong workflow:**  
> Locate (tìm thông tin sản phẩm / policy) và Prepare (soạn câu trả lời đúng context)

**AI leverage point chính:**  
> Locate + Prepare: từ câu hỏi khách → draft trả lời dựa trên catalog + policy + tone shop, kèm bước duyệt trước khi gửi

**Product hypothesis:**  
> Nếu giúp chủ shop giải quyết câu hỏi trước mua nhanh và chính xác hơn ở Locate + Prepare, họ sẽ chuyển từ ChatGPT + mẫu câu Notes sang ShopReply vì tiết kiệm 2–3 phút/tin và giảm trả lời sai trong giờ cao điểm.

**Assumption cần validate đầu tiên:**  
> A4 — AI có tra cứu catalog/policy shop đủ chính xác để draft đáng tin, hay chỉ viết đẹp nhưng sai fact.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
