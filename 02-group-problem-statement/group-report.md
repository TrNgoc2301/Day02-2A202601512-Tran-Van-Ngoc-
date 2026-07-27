# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   | Lê Thị Hải Yến | 2A202601570 |  |
| 2   | Đặng Hữu Khanh | 2A202601104 |  |
| 3   | Trần Văn Ngọc | 2A202601512 |  |
| 4   | Nguyễn Đức Anh | 2A202601870 |  |

---

# 02 — Group Problem Statement

## Group convergence

Nhóm 4 người, mỗi người share top candidate của mình. Tổng cộng khoảng 10 candidates.

| Cluster | Candidate examples | Pattern chung |
|---|---|---|
| Tổng hợp thông tin định kỳ | Báo cáo tiến độ đồ án hàng tuần (Yến), Báo cáo lab hàng tuần, theo dõi tiến độ ticket ngoài phạm vi chuyển cấp trên | Gom thông tin rải rác rồi trình bày lại cho người khác đọc/theo dõi định kỳ |
| Tra cứu / tổng hợp từ nhiều nguồn rời rạc | Tìm quyết định cũ trong Discord/Zalo (Yến), **Kiểm tra deadline từ nhiều nguồn (LMS, email, chat, lịch họp)**, Đọc paper để hiểu method | Phải tự ghép thông tin từ nhiều nơi, nhiều định dạng khác nhau để ra một câu trả lời đúng |
| Trả lời yêu cầu lặp lại theo mẫu | Trả lời ticket lặp lại, copy-paste mail mẫu trả lời khách hàng | Việc lặp lại gần như y hệt nhau, phần lớn có thể chuẩn hóa/tự động |
| Setup / onboarding quy trình | Setup lại cấu trúc dự án nhóm (Yến), Quy trình nhận và nộp bài khó hiểu với học viên mới | Người mới hoặc mỗi lần bắt đầu đều phải dựng lại/học lại từ đầu vì thiếu chuẩn hóa |

## Shortlist và score

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Kiểm tra deadline từ nhiều nguồn** | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| Báo cáo tiến độ hàng tuần | 5 | 5 | 3 | 4 | 4 | 4 | 4 | 29 |
| Trả lời ticket lặp lại | 4 | 5 | 4 | 4 | 3 | 4 | 3 | 27 |
| Tìm quyết định cũ Discord/Zalo | 4 | 4 | 3 | 3 | 3 | 4 | 4 | 25 |
| Quy trình nộp bài khó hiểu học viên mới | 4 | 4 | 4 | 3 | 4 | 3 | 3 | 25 |

Nhóm chọn: **Kiểm tra deadline từ nhiều nguồn**.

Vì sao chọn:

- Không phải pain riêng của một người hay một công việc cụ thể — cả 4 thành viên đều tự nhận ra mình gặp vấn đề này, dù đang học, làm research hay đi thực tập.
- Workflow rõ và có thể vẽ ngay: mở từng nguồn → tìm thông tin deadline → ghi lại → cập nhật lịch cá nhân.
- Không cần quyền truy cập dữ liệu nhạy cảm (khác với ticket công ty hay lịch sử chat riêng tư của nhóm khác).
- Có thể so sánh rõ Rule (đồng bộ nguồn có cấu trúc) và AI/Workflow (đọc nguồn phi cấu trúc như email, chat).

Vì sao không chọn các bài khác:

- Báo cáo tiến độ hàng tuần: pain thật nhưng gắn với một hoàn cảnh cụ thể (làm đồ án tốt nghiệp/lab), không phổ biến với tất cả thành viên trong buổi lab.
- Trả lời ticket lặp lại: impact rõ và lớn, nhưng chỉ một thành viên hiểu rõ domain, cần dữ liệu ticket thật của công ty nên khó làm trong phạm vi buổi lab.
- Tìm quyết định cũ Discord/Zalo: cần quyền truy cập lịch sử chat của nhóm khác, scope dễ phình to thành một hệ thống search/agent lớn.
- Quy trình nộp bài khó hiểu học viên mới: hướng giải quyết nghiêng hẳn về Non-AI/Process Fix, ít đất để so sánh Rule/Workflow/Agent.

## Quick validation

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Tự đánh giá lại trong 4 thành viên nhóm | 4 | Cả 4 người đều xác nhận từng trễ hoặc quên deadline vì thông báo nằm rải rác ở LMS, email, nhóm chat, lịch học | Thành viên làm helpdesk cho biết công việc ticket của bạn ít gặp vấn đề này hơn vì đã có SLA tracker riêng của công ty | Thu hẹp phạm vi: tập trung vào deadline học tập/sinh viên, không mở rộng sang các domain đã có công cụ theo dõi sẵn |
| Mini poll nhanh trong nhóm chat lớp K4 | ~8 | Đa số từng phải hỏi lại hoặc quên deadline vì thông tin nằm ở nhiều nơi khác nhau (LMS, Discord, email) | Một vài bạn nói đã có thói quen tự ghi lịch thủ công nên ít bị ảnh hưởng | Thêm non-AI alternative: một phần vấn đề là thói quen cá nhân, nên AI/tool chỉ nên hỗ trợ chứ không thay thế hoàn toàn việc tự quản lý lịch |

Insight sau validation:

```text
Pain thật không nằm ở việc "không có công cụ quản lý lịch" — hầu hết mọi người đều có
sẵn Google Calendar hoặc task app. Pain nằm ở đoạn deadline được thông báo bằng ngôn ngữ
tự nhiên, rải rác ở nhiều nguồn (đặc biệt là email và chat), nên phải tự đọc và nhập lại
thủ công vào nơi mình theo dõi.
```

## Research giải pháp

Nhóm tìm các hướng đã có sẵn, không giả định phải tự build từ đầu.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| TickTick — Smart Date Parsing | https://help.ticktick.com/articles/7055782422935240704 | Tự nhận diện ngày giờ trong nội dung gõ tay để tạo task, không cần chọn ngày thủ công | Nhanh, giảm thao tác nhập tay | Chỉ hoạt động khi người dùng tự gõ nội dung vào app, không tự đọc từ LMS/email/chat hộ mình | Rule/parser nhận diện ngày giờ trong text là bài toán đã có giải pháp sẵn, nhóm không cần tự xây từ đầu |
| Gemini trong Gmail — Add to Calendar | https://workspaceupdates.googleblog.com/2025/03/add-events-to-google-calendar-using-gemini-in-gmail.html | AI phát hiện nội dung liên quan lịch trong email và đề xuất thêm vào Google Calendar | Giảm thao tác thủ công; người dùng chỉ cần bấm xác nhận trước khi lưu | Hiện chủ yếu hoạt động tốt với các định dạng email quen thuộc, chưa bao phủ chat nhóm hay nội dung phi cấu trúc phức tạp | Pattern tốt để học theo: AI chỉ đề xuất, người dùng vẫn phải xác nhận trước khi lưu vào lịch — đúng kiểu human boundary nhóm cần |
| LMS Calendar Feed (iCalendar/ICS) | https://wpamelia.com/how-to-add-class-schedule-to-google-calendar/ | Đồng bộ tự động deadline bài tập từ LMS (Canvas, Google Classroom...) sang Google Calendar qua feed URL, tự cập nhật khi giảng viên đổi deadline | Không cần thao tác lại mỗi khi deadline thay đổi | Chỉ đồng bộ được nguồn hỗ trợ xuất feed chuẩn; deadline nhắc qua email hoặc tin nhắn chat vẫn không tự vào được | Rule/tích hợp có sẵn đã giải quyết tốt phần "nguồn có cấu trúc" (LMS); phần nhóm cần tập trung là nguồn phi cấu trúc (email, chat) |

Research takeaway:

```text
Không cần build agent tự động toàn bộ ngay từ đầu. Hướng hợp lý hơn: kết hợp Rule (đồng
bộ các nguồn đã có cấu trúc sẵn như LMS feed, calendar) với AI hỗ trợ đọc và trích xuất
deadline từ nguồn phi cấu trúc (email, tin nhắn chat), người dùng luôn xác nhận trước khi
lưu vào lịch trung tâm.
```

## Workflow before/after

File nhóm nộp kèm:

```text
02-group-problem-statement-workflow.png/pdf/md
```

Nội dung workflow:

```text
CURRENT STATE — ước tính ban đầu, cần đo thêm

[1 Mở LMS: 3']
→ [2 Mở email: 3']
→ [3 Đọc nhóm chat: 5']
→ [4 Mở calendar/task tool: 2']
→ [5 Tìm thông báo có deadline trong từng nguồn: 8']  <-- bottleneck
→ [6 Ghi ngày giờ thủ công vào lịch cá nhân: 3']
→ [7 Kiểm tra lại khi gần hạn: 3']

Tổng ước tính: ~20-25 phút/lần kiểm tra, lặp lại vài lần/tuần.

FUTURE STATE

[1 LMS đồng bộ tự động qua Calendar Feed: 0']  -- Rule
→ [2 Email/chat có deadline được AI nhận diện + trích xuất: 1']  -- Workflow step
→ [3 AI tạo draft task/event: 1']  -- Workflow step
→ [4 Sinh viên kiểm tra và xác nhận: 3']  <-- human boundary
→ [5 Task/event vào lịch trung tâm: 0']
→ [6 Rule nhắc hạn tự động]

Fallback:
AI nhận diện sai hoặc ngày giờ mơ hồ → giữ lại trong hộp thư chưa xử lý, sinh viên mở
nguồn gốc và nhập thủ công như cũ.

Bottleneck mới:
Sinh viên kiểm tra và xác nhận draft. Đây là bottleneck chấp nhận được vì đó là điểm
kiểm soát chất lượng trước khi deadline được ghi chính thức.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Thời gian kiểm tra deadline | ~20-25 phút/lần | Dưới 10 phút/lần | Target chính, cần đo thực tế trong 1-2 tuần đầu |
| Số nguồn phải tự mở | 4 (LMS, email, chat, calendar) | 1 (lịch trung tâm) | LMS và calendar tự đồng bộ qua Rule |
| Bước thủ công | 7/7 | 1/6 (bước xác nhận) | Sinh viên vẫn luôn là người chốt cuối |
| Bottleneck chính | Tìm thông báo trong từng nguồn | Kiểm tra + xác nhận draft | Chuyển từ "tìm" sang "kiểm tra", đúng human boundary |
| Risk mới | Không có AI hallucination | Có rủi ro AI nhận diện sai ngày/giờ | Cần review trước khi lưu chính thức |

## Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên/học viên phải theo dõi deadline từ nhiều nguồn cùng lúc (LMS, email, nhóm chat, lịch họp, công cụ quản lý task). |
| **Workflow** | Mở lần lượt từng nguồn, tìm thông báo có deadline, ghi lại thủ công, so sánh với lịch cá nhân, cập nhật task list/calendar. |
| **Bottleneck** | Bước tìm và đọc thông báo trong từng nguồn riêng lẻ, đặc biệt là email và chat, mất nhiều thời gian và dễ bỏ sót. |
| **Impact** | Ước tính 20-25 phút/lần kiểm tra, lặp lại vài lần/tuần; có nguy cơ nhập thiếu, nhập sai hoặc bỏ sót deadline dẫn đến trễ bài/trễ task. |
| **Success Metric** | Giảm thời gian kiểm tra deadline xuống dưới 10 phút/lần; 100% deadline mới được đưa vào lịch trung tâm trong 24 giờ; không bỏ sót deadline trong ít nhất 4 tuần thử nghiệm. |
| **Boundary** | AI không tự xác nhận ngày giờ mơ hồ, không tự xóa/sửa deadline đã có, không tự tạo task chính thức khi chưa được sinh viên xác nhận. |

## Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Đồng bộ tự động các nguồn có cấu trúc sẵn (LMS Calendar Feed, lịch họp) vào một calendar trung tâm | Đủ nếu deadline luôn nằm ở nguồn có cấu trúc rõ | Không giải quyết được deadline nằm trong email/chat viết bằng ngôn ngữ tự nhiên | Không chọn làm toàn bộ, nhưng dùng cho các nguồn có cấu trúc |
| **Workflow** | Rule đồng bộ nguồn có cấu trúc → AI nhận diện + trích xuất deadline từ email/chat → sinh viên xác nhận → vào calendar trung tâm | Hợp vì workflow tuyến tính, AI chỉ hỗ trợ đúng một bước (đọc hiểu ngôn ngữ tự nhiên) | Draft sai ngày giờ, cần sinh viên xác nhận trước khi lưu | Chọn |
| **Agent** | Agent tự đọc toàn bộ nguồn, tự quyết định độ ưu tiên, tự sắp lịch học, tự nhắc theo ngữ cảnh | Chỉ cần nếu muốn hệ thống tự lập kế hoạch học tập động, không chỉ dừng ở ghi nhận deadline | Quá rộng, cần nhiều quyền truy cập (email, chat riêng tư), rủi ro cao nếu tự sắp xếp sai | Chưa chọn |

Mức chọn:

```text
Workflow (kết hợp Rule cho nguồn có cấu trúc).
```

Vì sao:

- Phần nguồn có cấu trúc (LMS, lịch họp) giải quyết tốt bằng Rule, không cần AI.
- Phần nguồn phi cấu trúc (email, chat) cần AI để đọc hiểu ngôn ngữ tự nhiên và trích xuất đúng thông tin.
- Sinh viên vẫn xác nhận trước khi deadline được ghi chính thức nên rủi ro kiểm soát được.
- Chưa cần Agent vì nhóm chưa muốn AI tự quyết định thứ tự ưu tiên hay tự lên lịch học thay sinh viên.

## Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên/học viên phải theo dõi deadline từ nhiều nguồn cùng lúc (LMS, email, nhóm chat, lịch họp, công cụ quản lý task). |
| **Workflow** | Nguồn có cấu trúc đồng bộ tự động → nguồn phi cấu trúc (email, chat) được AI đọc và trích xuất → sinh viên xác nhận → deadline vào lịch trung tâm. |
| **Bottleneck** | Đọc và trích xuất đúng deadline từ email/chat viết bằng ngôn ngữ tự nhiên, dễ bỏ sót hoặc hiểu sai khi thông tin bị thay đổi. |
| **Impact** | Khoảng 20-25 phút/lần kiểm tra, lặp lại vài lần/tuần; rủi ro trễ deadline ảnh hưởng điểm số, tiến độ nghiên cứu hoặc đánh giá thực tập. |
| **Success Metric** | Giảm thời gian kiểm tra xuống dưới 10 phút/lần; 100% deadline mới vào lịch trung tâm trong 24 giờ; không bỏ sót deadline trong 4 tuần thử nghiệm. |
| **Boundary** | AI không tự xác nhận ngày giờ mơ hồ, không tự xóa/sửa deadline cũ, không tự tạo task chính thức khi chưa được xác nhận. |
| **AI intervention point** | Sau khi nhận được nội dung email/chat có khả năng chứa deadline, trước khi tạo draft task/event. |
| **Mức chọn** | Workflow: Rule đồng bộ nguồn có cấu trúc, AI trích xuất nguồn phi cấu trúc, sinh viên xác nhận. |
| **Rủi ro & người thật kiểm tra** | Risk: AI nhận diện sai ngày/giờ, bỏ sót deadline ẩn trong đoạn chat dài. Người thật kiểm tra: sinh viên xác nhận từng draft trước khi lưu chính thức. |

## Final decision

Decision:

```text
Go với scope nhỏ.
```

Pilot nhỏ nhất:

- Dùng dữ liệu mẫu: 1-2 tuần email/thông báo deadline thật của một thành viên nhóm.
- Đồng bộ thử LMS Calendar Feed vào một calendar trung tâm (phần Rule).
- Thử AI đọc và trích xuất deadline từ các email/tin nhắn mẫu đó, tạo draft task.
- Thành viên tự đo thời gian xác nhận draft và số lần AI trích sai ngày/giờ.

Exit / rollback:

- Nếu AI trích sai ngày/giờ quá thường xuyên (ví dụ trên 1/3 số draft trong 2 tuần), hạ xuống chỉ dùng Rule (đồng bộ nguồn có cấu trúc) + nhắc thủ công cho phần còn lại.
- Nếu việc xác nhận draft mất thời gian tương đương cách làm cũ, coi như chưa đủ giá trị để mở rộng thêm.

Decision rationale:

- Problem phổ biến với cả nhóm, không chỉ riêng một domain.
- Có phần giải được bằng Rule ngay, không phụ thuộc hoàn toàn vào AI.
- AI chỉ nằm ở đúng một bước cụ thể (đọc hiểu ngôn ngữ tự nhiên), không ôm toàn bộ workflow.
- Có human boundary rõ: sinh viên luôn là người xác nhận cuối cùng.