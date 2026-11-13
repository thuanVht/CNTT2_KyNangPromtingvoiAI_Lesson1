# Học code với AI: note nhanh

## Chia nhỏ prompt
Dàn ý → phần 1 → phần 2 → phần 3 → ghép lại. Mỗi bước đọc và sửa rồi mới đi tiếp, chỉ đưa tóm tắt phần trước cho đỡ tốn token.

## 1. AI đoán từ
- Giống gợi ý chữ khi nhắn tin, chỉ là to hơn nhiều
- Nó **đoán** câu nghe hợp lý, không phải câu chắc chắn đúng
- Nó đọc theo **token** (mẩu chữ), prompt dài thì tốn và dễ rối

## 2. Bắt bài AI chém gió (ảo giác)
1. Hàm, thư viện, link lạ → tra tài liệu chính thức
2. Chạy thử code, đừng tin lời nó
3. Hỏi lại cách khác, hỏi "dựa vào đâu?"

> Nó nói chắc ≠ nó nói đúng.

## 3. Khung CREATE
- **C**: vai trò (gia sư Python)
- **R**: cần nó làm gì
- **E**: 1 ví dụ mẫu
- **A**: giới hạn (≤150 từ, không chắc thì nói không chắc)
- **T**: dạng kết quả (3 mục...)
- **E**: dặn thêm (chỉ cách tự kiểm tra)

Lỗi hay gặp: hỏi quá chung chung, hoặc dán cả project để hỏi một dòng.

## Checklist
- [ ] Prompt đủ vai trò, yêu cầu, giới hạn, dạng kết quả
- [ ] Đã chạy thử code
- [ ] Hàm, thư viện, link có thật
- [ ] Hiểu code, không chỉ copy
