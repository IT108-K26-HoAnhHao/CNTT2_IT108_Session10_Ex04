
## Phần 1. Kiến trúc Prompt Hoàn chỉnh (Theo công thức 3 Phần)

Dưới đây là bản thiết kế Prompt áp dụng công thức 3 phần (Bối cảnh - Nội dung - Yêu cầu) bằng Markdown, tích hợp đầy đủ các ràng buộc và Task List:

```markdown
# 1. Bối cảnh (Context)
Bạn là một gia sư công nghệ thông tin tận tâm, giàu kinh nghiệm, chuyên hỗ trợ sinh viên năm 1 tiếp cận các kiến thức hệ thống phần cứng và tự động hóa nông nghiệp một cách dễ hiểu, gần gũi. Học viên đang gặp khó khăn khi tìm hiểu về **"Mô hình IPO (Input - Process - Output) trong trang trại thông minh"** và cần một góc nhìn trực quan, không dùng thuật ngữ quá phức tạp.

## 2. Nội dung (Content)
Hãy giải thích khái niệm **Mô hình IPO trong trang trại thông minh** (Ví dụ thực tế: Hệ thống tưới cây tự động dựa trên cảm biến độ ẩm đất). Bạn cần làm rõ 3 thành phần cốt lõi:
- **Input (Đầu vào):** Dữ liệu thu thập từ các cảm biến môi trường (như độ ẩm đất, nhiệt độ, ánh sáng).
- **Process (Xử lý):** Vi điều khiển (như Raspberry Pi hoặc Arduino) xử lý, so sánh dữ liệu thu thập được với ngưỡng cài đặt trước.
- **Output (Đầu ra):** Hành động thực tế của hệ thống (như bật/tắt máy bơm nước, phát cảnh báo).

## 3. Yêu cầu (Task List & Ràng buộc)
- [ ] Giải thích từng thành phần của mô hình IPO bằng ngôn ngữ đời thường, ngắn gọn, dễ hiểu nhất cho sinh viên năm 1.
- [ ] Đưa ra một ví dụ thực tế cụ thể xuyên suốt (ví dụ: vườn lan hoặc vườn rau sạch tự động).
- [ ] Trình bày câu trả lời bằng Markdown có cấu trúc rõ ràng (sử dụng danh sách liệt kê và in đậm các từ khóa quan trọng).

## Không cần
- Không giải thích bằng các đoạn mã lập trình (code) phức tạp.
- Không sử dụng quá nhiều thuật ngữ chuyên ngành mạng máy tính hoặc cấu trúc dữ liệu nâng cao ngoài phạm vi sinh viên năm 1.
```

# PHẦN 2. SẢN PHẨM: CÂU TRẢ LỜI CỦA AI SAU KHI ÁP DỤNG PROMPT

## 1. Giới thiệu

Mô hình IPO (Input – Process – Output) là mô hình mô tả quá trình tiếp nhận thông tin đầu vào, xử lý thông tin và tạo ra kết quả đầu ra.

Để hiểu rõ hơn về mô hình IPO trong trang trại thông minh, chúng ta sẽ tìm hiểu qua ví dụ **hệ thống tưới cây tự động**.

Mô hình IPO hoạt động giống như một chuỗi hành động phản xạ của con người:

**Input (Đầu vào) → Process (Xử lý) → Output (Đầu ra)**

## 2. Phân tích mô hình IPO trong hệ thống tưới cây tự động

### 2.1. Input (Đầu vào)

Input là dữ liệu được thu thập từ môi trường, giống như giác quan của con người.

Trong hệ thống tưới cây tự động, cảm biến độ ẩm được đặt trong đất để liên tục đo độ ẩm. Khi đất khô, cảm biến sẽ gửi dữ liệu về trung tâm điều khiển.

### 2.2. Process (Xử lý)

Process là quá trình xử lý thông tin, đóng vai trò như bộ não của hệ thống.

Bộ điều khiển nhận dữ liệu từ cảm biến, sau đó so sánh độ ẩm hiện tại với mức độ ẩm tiêu chuẩn đã được cài đặt. Nếu độ ẩm thấp hơn mức quy định, hệ thống sẽ gửi lệnh bật máy bơm nước.

### 2.3. Output (Đầu ra)

Output là kết quả hoặc hành động được tạo ra sau quá trình xử lý.

Khi nhận được lệnh từ bộ điều khiển, máy bơm nước sẽ tự động hoạt động để tưới cây. Khi độ ẩm đạt mức yêu cầu, hệ thống sẽ tắt máy bơm.

## 3. Quy trình hoạt động của mô hình IPO

Quy trình hoạt động của hệ thống tưới cây tự động được mô tả như sau:

1. **Input:** Cảm biến đo độ ẩm của đất và gửi dữ liệu về bộ điều khiển.
2. **Process:** Bộ điều khiển phân tích dữ liệu và so sánh với mức độ ẩm tiêu chuẩn.
3. **Output:** Nếu đất khô, máy bơm được bật để tưới nước. Khi đất đủ ẩm, máy bơm sẽ dừng.

## 4. Kết luận

Mô hình IPO giúp tự động hóa quá trình chăm sóc cây trồng trong trang trại thông minh. Nhờ sự kết hợp giữa cảm biến, bộ điều khiển và máy bơm nước, hệ thống có thể tưới cây theo nhu cầu thực tế mà không cần con người phải trực tiếp theo dõi liên tục.

Qua ví dụ trên, có thể thấy mô hình IPO giúp tiết kiệm thời gian, giảm công sức lao động và sử dụng nguồn nước hiệu quả hơn.


