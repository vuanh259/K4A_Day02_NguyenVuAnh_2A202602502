# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Vũ Anh
- Mã học viên: 2A202602502
- Nhóm: Zone B - Công Ty TNHH 1 mình tôi
- Candidate problem nhóm chọn: Sinh viên sử dụng Discord cho việc học phải dành khoảng 20-30 phút mỗi ngày để đọc và lọc nhiều channel nhằm tìm task, assignment, deadline hoặc thay đổi lịch, nhưng vẫn có nguy cơ bỏ sót thông tin cần hành động.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 10 vấn đề thực tế trong học tập và công việc; chọn top 3 bài toán có actor rõ ràng và workflow đo lường được (trong đó có bài #18 theo dõi deadline Discord). | Đóng góp 3 Problem Card chi tiết vào kho ý tưởng chung, tạo tiền đề mạnh mẽ cho vòng hội tụ của nhóm. |
| Pitch Problem Card | Trình bày bài #18, chỉ rõ bottleneck sinh viên mất 20-30 phút/ngày lọc tin nhắn và nguy cơ lỡ deadline; trực tiếp mở 3 server Discord lớp học làm bằng chứng. | Thuyết phục cả nhóm nhận diện đây là pain chung có thật, cấp thiết và hoàn toàn khả thi để kiểm chứng trong buổi lab. |
| Challenge bài của bạn khác | Phản biện bài của Duy (tìm đồ Xanh SM, trạm sạc VinFast ảo) và Hoàng (thủ tục hành chính, bãi đỗ xe) vì phụ thuộc telemetry/camera và hạ tầng bên thứ ba ngoài tầm với; phản biện bài của Lương (chấm lỗi SV - rủi ro học thuật lớn; order món bếp - Rule/Form là đủ); phản biện bài của Đạt (đổi lịch - checklist đủ; gom đánh giá 8h - dữ liệu nội bộ riêng). | Giúp nhóm nhanh chóng loại bỏ các bài toán quá rộng, rủi ro cao hoặc giải quyết được bằng Non-AI, thu hẹp phạm vi thảo luận hiệu quả. |
| Gom trùng / cluster | Phân tích 18 candidate của 6 thành viên (Lương, Hoàng, Duy, Đạt, Việt Anh và tôi) vào 4 cụm logic; phát hiện sự trùng lặp về nỗi đau thông báo Discord giữa bài #3 của Việt Anh và bài #18 của tôi. | Giúp nhóm có cái nhìn bao quát 18 ý tưởng thành 4 cụm rõ ràng, tiết kiệm thời gian hội tụ. |
| Chọn candidate problem | Bảo vệ bài #18 trước bài #11 (Đạt) và #1 (Lương); chứng minh tính khả thi vượt trội về dữ liệu và khả năng kiểm chứng trực tiếp trong lab; phản biện đề xuất làm Agent của Việt Anh để đưa về Workflow. | Nhóm đạt đồng thuận tuyệt đối với số điểm cao nhất (33/35 điểm), chính thức chọn bài #18 làm candidate problem duy nhất. |
| Validation / research | Thực hiện phỏng vấn nhanh và khảo sát sinh viên về tần suất kiểm tra Discord; nghiên cứu sâu các tool hiện có như Zapier Discord-to-Todoist, Zapier Calendar và Motion AI. | Làm rõ insight: pain thật nằm ở bước hiểu ngữ cảnh ngôn ngữ tự nhiên; vạch ra khoảng trống của các giải pháp hiện tại để nhóm không làm lại cái đã có. |
| Workflow nhóm | Đóng góp ý tưởng tối ưu hóa workflow: đề xuất kiến trúc Hybrid xử lý Real-time qua webhook; bổ sung tính năng Cá nhân hóa (tùy chỉnh trọng số người gửi/kênh quan tâm); tích hợp Smart Calendar Reminder (nhắc trước sự kiện như workshop tối 8h) và Daily Focus Chatbot để sinh viên tra cứu lại các việc quan trọng trong ngày; giữ vững Human Boundary (Confirm/Edit/Ignore). | Cắt giảm thời gian kiểm tra từ 25 phút xuống dưới 10 phút/ngày; giải quyết trọn vẹn tình trạng sinh viên quên lịch/deadline sát giờ và giúp tái tập trung nhanh chóng. |
| Problem Statement | Cùng nhóm hoàn thiện bản Problem Statement v1: siết chặt boundary (chỉ quét channel được cấp quyền, không đọc DM, không xử lý LMS/email) và lượng hóa success metric. | Đảm bảo bản Problem Statement đạt chuẩn: metric đo được (recall ≥90%, accuracy ≥95%), boundary có làm/không làm rõ ràng. |
| Rule / Workflow / Agent | Trình bày và phản biện khi bạn Việt Anh và nhóm có xu hướng muốn làm "Autonomous Agent "; chứng minh bài toán có quy trình cố định nên chỉ cần dừng ở mức Workflow. | Giúp nhóm không bị sa vào bẫy "solution-first", giữ giải pháp tinh gọn, tiết kiệm chi phí tính toán và kiểm soát được rủi ro ảo giác. |
| Decision | Đề xuất quyết định Go cho pilot nhỏ (100 message ẩn danh) và Not Yet cho production; trực tiếp đại diện nhóm giải thích luồng bài toán và phản biện với các nhóm khác trong lớp. | Nhóm thống nhất lộ trình rõ ràng; các nhóm khác trong lớp hiểu rõ tính khả thi và mạch logic chặt chẽ của giải pháp. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người đề xuất và bảo vệ candidate problem gốc (#18), đồng thời trực tiếp đóng góp các ý tưởng tối ưu hóa cốt lõi: xử lý Real-time, cá nhân hóa trọng số quan tâm, nhắc lịch thông minh trước giờ G (Smart Calendar Reminder) và trợ lý Daily Focus Chatbot giúp sinh viên không bao giờ bỏ sót sự kiện quan trọng.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Brainstorm mở rộng các góc nhìn về công việc lặp lại và tốn thời gian. | Gợi ý nhiều bối cảnh và lĩnh vực công việc đa dạng để tham khảo. | Đưa ra các ý tưởng quá chung chung, vĩ mô kiểu "quản lý cuộc sống bằng AI", không có actor hay workflow cụ thể. | Gạt bỏ toàn bộ các ý tưởng sáo rỗng, tự chọn và đo lường các pain-point từ chính trải nghiệm thực tế hằng ngày (tìm chat cũ, so giá, theo dõi deadline). |
| Problem Card | Gợi ý khung sườn bóc tách các bước trong current workflow. | Giúp chuẩn hóa cấu trúc 3-7 bước rõ ràng và xác định các điểm handoff. | Mô tả luồng công việc quá hoàn hảo và tuyến tính, bỏ qua việc người dùng nhớ sai từ khóa hoặc bị ngắt quãng. | Bổ sung bottleneck chi tiết về việc tìm kiếm phụ thuộc vào keyword chính xác và đề xuất các phương án non-AI dự phòng. |
| Workflow | Tham khảo cách phân định trách nhiệm giữa Rule tự động và module AI. | Liệt kê đầy đủ các trường thông tin cần trích xuất (sender, action, deadline, urgency, relevance). | Luôn thiên vị tự động hóa 100%, gợi ý để AI tự động ghi thẳng task vào Google Calendar mà không cần người duyệt. | Tối ưu lại quy trình: kiên quyết chèn Human Boundary bắt buộc (Confirm/Edit/Ignore) và cơ chế tính Priority Score bằng Rule để bảo đảm an toàn. |
| Research | Tra cứu cơ chế hoạt động và tính năng của Zapier Discord Integration và Motion AI. | Tổng hợp nhanh các trigger/action sẵn có và cách xếp lịch tự động của các công cụ hiện nay. | Khen ngợi một chiều, không chỉ ra được điểm yếu cốt tử của các tool hiện có khi gặp tin nhắn giao việc phi cấu trúc. | Tự phân tích khoảng trống của các giải pháp hiện có (chỉ bắt được từ khóa/trigger cứng) và vạch ra định hướng nâng cấp hệ thống trong tương lai. |
| Problem Statement | Đóng vai phản biện để rà soát các lỗ hổng trong Problem Statement v0. | Phát hiện ra cụm từ "tin nhắn quan trọng" còn mơ hồ, mang nặng tính cảm tính. | Đề xuất các metric viển vông, khó đo đạc trong thực tế lab (ví dụ: "tăng 30% hiệu quả học tập toàn diện"). | Viết lại định nghĩa tin nhắn quan trọng bằng 6 tiêu chí định lượng; siết chặt metric kỹ thuật (recall ≥90%, accuracy ≥95%, false positive ≤2/ngày). |
| Rule / Workflow / Agent | So sánh ưu nhược điểm kỹ thuật giữa 3 mức Rule, Workflow và Agent. | Cung cấp khung lý thuyết so sánh dựa trên 2 trục: độ mơ hồ và độ phức tạp. | Cổ xúy làm Autonomous Agent tự lập kế hoạch đa bước vì nghe "thông minh và xu hướng" hơn. | Phản biện lại AI, kiên định bảo vệ phương án Workflow vì các bước xử lý đã cố định, không cần Agent tự lập kế hoạch gây rủi ro ảo giác và tốn kém. |
| Decision | Không dùng | Không dùng | Không dùng | Tự cùng nhóm đánh giá mức độ sẵn sàng của dữ liệu pilot (100 message ẩn danh) và năng lực thực thi trong lab để đưa ra quyết định thực tế: Go với pilot, Not Yet với production. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi lắng nghe top 3 problem của các bạn trong nhóm, tôi học được bài học sâu sắc về tính khả thi của bài toán: các đề xuất của Duy (tìm đồ Xanh SM, sự cố trạm sạc VinFast) hay Hoàng (thủ tục hành chính, tìm chỗ đỗ xe) tuy rất thực tế nhưng phụ thuộc nặng nề vào hạ tầng và dữ liệu kín của bên thứ ba, trong khi bài của Lương (order bếp) và Đạt (đổi lịch) hoàn toàn có thể giải quyết bằng Form hoặc Rule mà chưa cần đến AI. Đặc biệt, khi bạn Việt Anh cũng đưa ra vấn đề theo dõi thông báo Discord và gợi ý làm một AI Agent tự động, nhóm đã có lúc bị cuốn vào tư duy "solution-first" và muốn làm Agent cho thật ngầu. Trước tình huống đó, tôi đã chủ động pitch bài #18 của mình, đưa bằng chứng thực tế từ các server lớp và phản biện gay gắt rằng việc trao toàn quyền cho Agent tự lên lịch sẽ tạo ra rủi ro nghiêm trọng nếu AI trích xuất sai ngày giờ bài tập lớn. Để tối ưu hóa giải pháp, tôi đóng góp ý tưởng xây dựng một Workflow lai (Hybrid) xử lý theo thời gian thực (Real-time): kết hợp Rule tính điểm ưu tiên với cấu hình cá nhân hóa người dùng (chọn người gửi hoặc kênh cần quan tâm hơn), AI chỉ can thiệp ở bước hiểu ngôn ngữ tự nhiên, và bắt buộc đặt bước con người duyệt (Confirm/Edit/Ignore) làm ranh giới an toàn. Bên cạnh đó, tôi trực tiếp đề xuất hai tính năng giải quyết trọn vẹn trải nghiệm sinh viên: Smart Calendar Reminder tự động nhắc trước sự kiện (ví dụ nhắc trước 30 phút khi tối nay 8h có workshop để không bị quên) và Daily Focus Chatbot cho phép sinh viên chat hỏi lại những việc quan trọng trong ngày để nhanh chóng tái tập trung khi bị ngợp. Trong phần nghiên cứu thị trường, tôi đã phân tích các công cụ hiện có như Zapier Discord-to-Todoist hay Motion AI và chỉ rõ khoảng trống của chúng là chỉ xử lý được trigger hoặc keyword cứng, hoàn toàn bất lực trước những tin nhắn giao việc gián tiếp trong chat. Từ hạn chế đó, tôi đề xuất định hướng nâng cấp hệ thống trong tương lai bằng cách kết nối mở rộng sang LMS và Email trường, kết hợp phân tích chuỗi hội thoại dài (conversation context) để không bỏ sót các cập nhật trong thread trao đổi. Tại phiên phản biện chéo giữa các nhóm, tôi đã đại diện nhóm trực tiếp trình bày và giải thích mạch tư duy logic từ Problem, Workflow đến Boundary, giúp các nhóm bạn hiểu rõ vì sao nhóm tôi ưu tiên chọn bài toán Discord và kiên quyết dừng ở mức Workflow thay vì chạy theo Agent theo trào lưu. Nhờ những luận điểm thực tế và bằng chứng trực quan từ các channel Discord thật, tôi đã bảo vệ thành công đề tài gốc và định hình trọn vẹn cấu trúc workflow tối ưu, giúp nhóm đạt điểm đồng thuận tuyệt đối 33/35. Bài học lớn nhất mà tôi đúc kết được sau buổi làm việc là giá trị của sự kiềm chế công nghệ: một hệ thống thông minh không phải là để AI làm thay tất cả, mà là biết ứng dụng AI đúng điểm nghẽn thực sự, hỗ trợ người dùng đúng lúc và luôn giữ vững quyền kiểm soát cao nhất ở tay con người.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

