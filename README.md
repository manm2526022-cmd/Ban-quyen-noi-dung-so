# Ban-quyen-noi-dung-so
# Phân tích cảm xúc bình luận tiếng Việt trên mạng xã hội (Vietnamese Sentiment Analysis)

## 1. Giới thiệu & Mục tiêu
Dự án này tập trung xây dựng mô hình học sâu nhằm tự động phân loại cảm xúc (Tích cực, Tiêu cực, Trung tính) từ các bình luận tiếng Việt trên nền tảng thương mại điện tử và mạng xã hội.

## 2. Phương pháp thực hiện
- **Tiền xử lý dữ liệu:** Chuẩn hóa từ viết tắt, teencode, tách từ tiếng Việt bằng thư viện `underthesea`.
- **Mô hình:** Huấn luyện và tinh chỉnh (fine-tuning) mô hình ngôn ngữ tiền huấn luyện **PhoBERT**.

## 3. Kết quả đạt được
- Độ chính xác (Accuracy) trên tập kiểm thử đạt **91.4%**.
- F1-score trung bình đạt **0.91**.

## 4. Cấu trúc thư mục
- `data/`: Chứa tập dữ liệu mẫu đã qua tiền xử lý.
- `src/`: Mã nguồn huấn luyện và đánh giá mô hình.
- `docs/`: Tài liệu báo cáo khoa học và poster.
- `results/`: Biểu đồ ma trận nhầm lẫn (Confusion Matrix) và log huấn luyện.

## 5. Giấy phép (License)
Dự án này được phát hành theo giấy phép **MIT License**. Xem chi tiết tại file [LICENSE](LICENSE).
