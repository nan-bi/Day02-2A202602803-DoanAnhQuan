# 03 — Individual Reflection

> Bài tự soi và đúc kết cá nhân sau buổi làm việc nhóm (Phase 7).

## Thông tin cá nhân

- Họ và tên: Trần Thị Lan
- Mã học viên: 2A202602621
- Nhóm: Nhóm cuối - Zone B
- Candidate problem nhóm chọn: Trợ lý AI hỗ trợ giao tiếp hai chiều với người sử dụng ngôn ngữ ký hiệu tại quầy dịch vụ

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| **Scan cá nhân** | Đóng góp 12 problem quan sát từ thực tế học tập và làm việc. | Cung cấp cho nhóm nhiều góc nhìn đa dạng và phong phú. |
| **Pitch Problem Card** | Đóng góp 3 problem cards chi tiết, trực tiếp pitch & trình bày các ý tưởng. | Giúp nhóm có 3 hướng đi cụ thể để phân tích và đánh giá. |
| **Challenge bài của bạn khác** | Phản biện sâu, đặt câu hỏi về tính khả thi, rủi ro bảo mật và độ rộng thị trường. | Giúp nhóm hiểu sâu bản chất điểm nghẽn và điều chỉnh định hướng đề tài. |
| **Gom trùng / cluster** | Phân tích ưu/nhược điểm, phân loại 12 candidate thành 4 cụm bài toán (Accessibility, Dev process, Study tools, Data utilities). | Thu hẹp phạm vi chọn lựa một cách hệ thống. |
| **Chọn candidate problem** | Đưa ra góc nhìn kỹ thuật, thảo luận về giải pháp nhận diện cử chỉ và tính khả thi trong 1 ngày lab. | Thống nhất chốt đề tài Cầu nối Ngôn ngữ ký hiệu (#8 - Nam). |
| **Validation / research** | Nghiên cứu tài liệu kỹ thuật (Google MediaPipe Gesture Recognizer, SignAll Kiosk), đọc khảo sát và tài liệu về cộng đồng người khiếm thính. | Làm rõ mô hình kiến trúc Hybrid (Edge AI Vision + LLM + STT/TTS). |
| **Workflow nhóm** | Góp ý thiết kế luồng Current State (225s) và Future State (25s) hai chiều. | Xác định rõ 5 bước liền mạch, Human boundary và phương án Fallback. |
| **Problem Statement** | Tham gia chuẩn hóa nội dung Problem Statement từ v0 sang v1. | Thống nhất định nghĩa Actor, Bottleneck, Metric và Boundary chặt chẽ. |
| **Rule / Workflow / Agent** | Thảo luận ma trận độ phức tạp/mơ hồ và phân tích 3 cấp độ kiến trúc. | Chốt chọn giải pháp **Workflow** (kết hợp Human-in-the-loop). |
| **Decision** | Tổng hợp bằng chứng, thống nhất tiêu chí Go/No-Go và xây dựng kế hoạch Pilot. | Chốt quyết định GO với phạm vi Pilot quầy thanh toán tiện lợi. |

**Dấu tay rõ nhất của tôi trong artifact cuối:**

Bản artifact mang "dấu tay" rõ nhất của tôi qua tư duy **Product Management sắc bén** (áp dụng trực tiếp mô hình *Workflow - Metrics - Impact*) kết hợp với góc nhìn thực tế của một **Kỹ sư AI/Architect** (đề xuất kiến trúc Edge AI với MediaPipe để xử lý real-time, giảm độ trễ và cân đối tính khả thi kỹ thuật trong phạm vi lab).

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan** | Gợi ý thêm các problem quan sát đời sống. | Đưa ra danh sách đa dạng góc nhìn ban đầu. | Đưa ra các bài toán chung chung, pain không có thực hoặc lặp lại ý. | Tôi chắt lọc, điền số liệu đo lường thực tế và điều chỉnh lại đúng định dạng mẫu. |
| **Problem Card** | Không dùng vì tự làm theo mẫu có sẵn và trải nghiệm cá nhân. | N/A | N/A | Tự xây dựng workflow, số đo và giả định AI. |
| **Workflow** | Đề xuất tối ưu luồng Future State và hỏi về tính thực tế kỹ thuật. | Đưa ra cấu trúc chuẩn học thuật và gợi ý linh hoạt. | Đôi lúc bị lệch đề, đưa ra workflow quá phức tạp hoặc chưa hợp lý ở đời thực. | Xem xét tính khả thi thực tế và điều chỉnh luồng interaction ngắn gọn (<25s). |
| **Research** | Tìm hiểu tài liệu kỹ thuật về MediaPipe Gesture Recognizer. | Tóm tắt nhanh tính năng của MediaPipe và Hand Landmarks. | Thiếu phân tích sâu về bối cảnh ngữ pháp ngôn ngữ ký hiệu Việt Nam. | Tự bổ sung giải pháp dùng LLM kết hợp để dựng câu tiếng Việt hoàn chỉnh. |
| **Problem Statement** | Không dùng (thành viên khác trong nhóm phụ trách tổng hợp). | N/A | N/A | Rà soát và đóng góp tiêu chí boundary. |
| **Rule / Workflow / Agent** | Phân loại và phân tích phân khúc kiến trúc hệ thống (Workflow vs Agent). | Giúp phân định giữa tối ưu quy trình có sẵn và lạm dụng Agent quá sớm. | Dễ vẽ ra các Agent tự động hóa quá phức tạp, rủi ro sai sót thanh toán cao. | Quyết định dừng ở mức **Workflow** có bước duyệt người dùng (Human-in-the-loop) để bảo đảm an toàn. |
| **Decision** | Tổng hợp và cấu trúc hóa lập luận cho quyết định Go/No-Go. | Cấu trúc thông tin mạch lạc, làm nổi bật metrics và impact. | Các số liệu đo lường ban đầu thường định tính, thiếu căn cứ hệ thống. | Tự đưa ra các mục tiêu thực tế (giảm thời gian từ 225s xuống <25s, chính xác >90%). |

---

## 3. Reflection câu hỏi mở

Sau khi nghe 3 problems của các bạn khác trong nhóm, tôi cảm thấy những bài toán cá nhân ban đầu của bản thân còn khá nhỏ và mang tính nội bộ. Chúng chưa phải là các ý tưởng mang tính đột phá hay tạo ra giá trị tác động xã hội rộng lớn, nhiều bài toán đã có giải pháp thương mại làm rất tốt trên thị trường. Bài học rút ra cho tôi là sau này cần suy nghĩ bài toán sắc sảo hơn, xoáy sâu vào những điểm nghẽn thiết yếu trong đời sống dù đơn giản nhưng mang lại giá trị cao cho người dùng.

Trong quá trình thảo luận, tôi cũng sẵn sàng thay đổi ý kiến sau khi bị nhóm phản biện. Bài toán "Tổng hợp Task đa kênh" của tôi dù có pain thật nhưng gặp rào cản lớn về kỹ thuật tích hợp API đa nền tảng và chính sách bảo mật dữ liệu. Ngược lại, khi phân tích bài toán "Cầu nối ngôn ngữ ký hiệu", ban đầu tôi và Việt Anh lo ngại về độ phức tạp của Computer Vision, nhưng sau khi nhóm chốt thu hẹp phạm vi (scoping) vào quầy thanh toán với 8-12 cử chỉ cốt lõi, tôi nhận thấy đây là hướng đi cực kỳ khả thi và tạo cảm hứng mạnh mẽ.

Nếu được làm lại, tôi sẽ challenge nhóm mạnh mẽ hơn ở phần xác định bài toán ngay từ đầu. Tôi sẽ yêu cầu mọi người đào sâu phân tích rào cản thói quen thực tế của nhân viên thu ngân và người khiếm thính thay vì chỉ dựa trên các giả định trên giấy, đồng thời thu thập thêm đa góc nhìn từ nhiều ngữ cảnh dịch vụ khác nhau để bộ cử chỉ có tính chuẩn hóa cao hơn.

---

## 4. Tự kiểm cuối bài

- [x] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] Nhóm có workflow trước/sau
- [x] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI