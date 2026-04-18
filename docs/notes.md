# Underthesea - Word Tokenize Notes

## Tách từ hoạt động như thế nào?

- Underthesea dùng mô hình NLP để tách từ tiếng Việt
- Không tách đơn giản theo dấu cách
- Các từ có nghĩa được ghép lại bằng dấu "_"

## Ví dụ

Input: "Tôi là sinh viên"
Output: ["Tôi", "là", "sinh_viên"]

Input: "Hôm nay đi học"
Output: ["Hôm_nay", "đi", "học"]

## Kết luận

- Tách từ giúp máy hiểu đúng nghĩa câu
- Quan trọng cho chatbot và NLP