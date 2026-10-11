# Đoán Ai? (Guess Who? bản tiếng Việt)

Board game **Guess Who?** chơi ngay trên trình duyệt, giao diện tiếng Việt, 24 nhân vật tên Việt (Hùng, Lan, Ông Ba, Bà Năm, …) được vẽ bằng SVG.

## Cách chơi
- Mỗi người được chia ngẫu nhiên 1 nhân vật bí mật trong 24 người.
- Đến lượt: hỏi 1 câu Có/Không về ngoại hình (tóc, kính, mũ, râu, màu áo…) **hoặc** đoán nhân vật của đối thủ.
- Câu hỏi chọn sẵn được trả lời tự động; lật úp những người không khớp (có nút hạ thẻ hộ).
- Đoán đúng thì thắng; đoán sai thì thua ngay (luật gốc) hoặc chỉ mất lượt (tùy chọn).

## Chế độ
- **Online 2 người** qua PeerJS: tạo phòng, gửi mã 5 ký tự hoặc link cho bạn bè.
- **Chơi với máy**: Dễ / Vừa / Khó (mức Khó tính xác suất thắng để quyết định hỏi hay đoán liều).
- Tùy chọn: tự động hạ thẻ, câu hỏi kép (HOẶC), câu hỏi tự do (đối thủ tự trả lời).

## Chạy thử
Chỉ cần mở `index.html` qua một web server tĩnh, ví dụ:

```bash
npx http-server . -p 5193
```
