---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** Stack Overflow  
**Người làm:** Nguyễn Thanh Lâm  
**Bàn / nhóm bàn:** Nhóm 1  
**Ngày:** 19/06/2026

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [x] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [x] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [x] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [x] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** Stack Overflow
- **AI / platform / sản phẩm mới tạo áp lực:** ChatGPT (OpenAI) và các AI coding assistants (GitHub Copilot, Cursor).
- **Vì sao tôi chọn case này?**  
  > Đây là một case điển hình về việc network effects (hiệu ứng mạng) bị đảo chiều hoàn toàn bởi Generative AI, khi user chuyển từ "hỏi cộng đồng" sang "hỏi AI".

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | Traffic giảm ~14% vào đầu năm 2023 ngay sau khi ChatGPT ra mắt | Dấu hiệu dòng người dùng bắt đầu chuyển entry point từ web sang chatbot. | Similarweb |
| E2 | Số lượng câu hỏi mới giảm mạnh (~16% trong 2023) | Nguồn cung cấp dữ liệu cho mạng lưới (UGC) bị đe dọa trực tiếp. | Báo cáo cộng đồng Stack Overflow |
| E3 | Sa thải 28% nhân sự vào tháng 10/2023 | Tác động tài chính rõ ràng khi chi phí vận hành không còn tương xứng với traffic/doanh thu quảng cáo. | TechCrunch / CEO Blog |
| E4 | Ra mắt OverflowAI vào tháng 7/2023 | Phản ứng pivot của công ty trước sức ép AI, cố gắng giữ chân user bằng AI. | Stack Overflow Blog |
| E5 | Bán quyền truy cập API dữ liệu cho OpenAI và Google | Pivot sang mô hình kinh doanh bán dữ liệu thay vì chỉ dựa vào quảng cáo traffic. | Reuters |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > Network effects khổng lồ: nội dung do người dùng tạo ra (UGC) tốt nhất, thu hút SEO số 1 trên Google cho các câu hỏi lập trình.
2. **AI shock làm thay đổi...**  
   > Thói quen tìm kiếm lỗi (debugging) từ việc tra Google/Stack Overflow sang hỏi trực tiếp chatbot AI và coding assistants ngay trong IDE.
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > Số lượng câu hỏi mới giảm mạnh, cho thấy "data flywheel" của Stack Overflow đang bị gãy và user tự tìm được câu trả lời cá nhân hóa.

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> Người dùng "thuê" Stack Overflow để tìm câu trả lời cho lỗi code từ cộng đồng. Họ thắng nhờ data advantages và network effects khổng lồ: càng nhiều câu hỏi/trả lời -> SEO càng mạnh -> càng nhiều người truy cập -> lại càng nhiều câu hỏi/trả lời.  
> Giả định cốt lõi là: cộng đồng crowdsource là cách nhanh nhất và chính xác nhất để giải quyết một lỗi lập trình cụ thể.

**Bằng chứng đỡ nhận định này:** E1, E2

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** Làm xong giúp tôi & Thấu hiểu ngữ cảnh.  
**Competitive dynamic quan trọng nhất:** Data advantages (AI đã cào hết data của Stack Overflow nên lợi thế dữ liệu web bị vô hiệu hóa).

**Trả lời của tôi:**  
> Kỳ vọng của user đã chuyển từ việc phải đọc nhiều thread, tự chắt lọc và copy/paste sang việc AI "thấu hiểu ngữ cảnh" code của họ và "làm xong giúp tôi" (đưa ra đoạn code sửa lỗi ngay lập tức).  
> Luật chơi cạnh tranh thay đổi khi data advantage của Stack Overflow bị các mô hình LLM hấp thụ. Họ không còn thế độc quyền về "câu trả lời đúng" nữa.

**Bằng chứng đỡ nhận định này:** E1, E4

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> Workflow cũ (Code lỗi -> Copy lỗi -> Lên Google -> Bấm vào Stack Overflow -> Đọc lướt -> Copy/paste lại) đã chết. Chuẩn mới là "Làm xong giúp tôi ngay trong nơi tôi đang làm việc" (IDE).  
> Entry point của lập trình viên đã vĩnh viễn chuyển từ trình duyệt web (tìm kiếm) sang IDE (AI assistant như Copilot/Cursor).

**Bằng chứng đỡ nhận định này:** E1, E2, E3

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh

**Trả lời của tôi:**  
> Có thể cứu được nhưng phải từ bỏ mô hình kinh doanh phụ thuộc vào page views/quảng cáo. Họ phải pivot trở thành nhà cung cấp dữ liệu bản quyền (Data-as-a-Service) cho các công ty AI để lấy phí API, vì AI vẫn cần dữ liệu mới nhất (human-validated) mà nó chưa từng được train.  
> Đồng thời, phải xây dựng AI tích hợp sâu vào IDE (OverflowAI) để giành lại entry point.

**Bằng chứng đỡ nhận định này:** E4, E5

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì AI đã giải quyết được nhu cầu debugging trực tiếp theo ngữ cảnh, phá vỡ network effect của diễn đàn hỏi đáp.  
2. Điều thay đổi vĩnh viễn là entry point của lập trình viên đã chuyển từ trình duyệt web sang các AI coding assistant ngay trong IDE.  
3. Verdict của tôi là Stack Overflow phải chuyển đổi mô hình kinh doanh từ quảng cáo/traffic sang bán dữ liệu bản quyền (API) và phát triển sản phẩm tích hợp IDE.

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Bạn 1 | Chegg | Mất 50% thuê bao chỉ trong một thời gian ngắn. | User không còn cần trả tiền cho lời giải tĩnh khi AI giảng giải sinh động hơn. | Phải pivot cực mạnh hoặc chết. |
| Bạn 2 | Jasper | Định giá chững lại, sa thải nhân sự. | Vỏ bọc (wrapper) mỏng bị lộ diện khi ChatGPT ngày càng rẻ và giỏi. | Không cứu được trừ khi có workflow riêng sâu. |
| Bạn 3 | Tome | Lượt sử dụng giảm mạnh. | AI phổ thông (như Copilot trong PowerPoint) làm tính năng tạo slide không còn là moat. | Đang thoi thóp. |
| Bạn 4 | Stack Overflow | Sa thải 28% nhân sự. | Entry point chuyển từ Web sang IDE. | Có thể sống nhờ bán data. |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> Case Stack Overflow và Chegg. Vì số liệu traffic và subscriber drop cực kỳ rõ rệt, kết hợp với các đợt sa thải lớn ngay lập tức sau AI shock, không thể chối cãi.

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> User chuyển sang "làm xong giúp tôi" (bỏ qua bước tìm kiếm/nghiên cứu). Moat cũ dựa trên SEO/Traffic và nội dung tĩnh bị phá vỡ hoàn toàn.

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> Đừng bao giờ dựa vào việc user phải rời khỏi workflow (context) hiện tại của họ để mở app của mình. Phải sở hữu entry point hoặc tích hợp sâu vào nơi họ đang làm việc.

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [ ] Giữ nguyên
- [x] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Tôi đổi nhẹ bằng cách nhấn mạnh hơn vào sự nguy hiểm của việc mất "workflow". Stack Overflow không chỉ mất traffic, họ mất quyền kiểm soát workflow của lập trình viên. 

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> Moat lớn nhất của họ là kho nội dung do người dùng tạo ra (UGC) và traffic từ Google đã bị AI "vô hiệu hóa" khi AI có thể cung cấp câu trả lời cá nhân hóa ngay lập tức. Họ đã mất kiểm soát workflow của người dùng.

**Điều thay đổi vĩnh viễn là:**  
> Entry point của quá trình code và fix bug đã chuyển vĩnh viễn từ trình duyệt web (tìm kiếm) sang IDE (AI assistant "làm xong giúp tôi").

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Không được xây dựng sản phẩm dựa trên một workflow tốn thời gian hay bắt user đổi context. Phải đưa AI vào đúng entry point của user để giảm thiểu "friction" (ma sát) và giải quyết trọn vẹn "job" tại chỗ.

---

## Checklist trước khi nộp

- [x] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [x] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [x] Tôi đã ghi lại phần share trong bàn.
- [x] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

- Bổ sung thêm một case "đối thủ phản ứng tốt hơn" để so.
- Thêm một đoạn ngắn: **nếu tôi là PM của case này trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?**
- Kiểm lại xem case này yếu vì expectation shift, competitive dynamics, hay cả hai cùng lúc.
