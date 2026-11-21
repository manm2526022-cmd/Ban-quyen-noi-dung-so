# Ban-quyen-noi-dung-so
# Hệ thống Phân tích Cảm xúc Bình luận Tiếng Việt (Vietnamese Sentiment Analysis)

## 1. Giới thiệu đề tài
Dự án xây dựng mô hình học máy nhằm tự động phân loại cảm xúc (Tích cực, Tiêu cực, Trung tính) từ các bình luận tiếng Việt trên nền tảng thương mại điện tử.

## 2. Mục tiêu
- Thu thập và tiền xử lý bộ dữ liệu 10.000 bình luận tiếng Việt.
- Huấn luyện và đánh giá độ chính xác của mô hình phân loại.
- Đóng gói thành thư viện mã nguồn mở phục vụ cộng đồng nghiên cứu.

## 3. Phương pháp thực hiện
- Làm sạch dữ liệu văn bản, tách từ tiếng Việt (sử dụng thư viện `underthesea`).
- Trích xuất đặc trưng bằng TF-IDF và huấn luyện mô hình Logistic Regression / PhoBERT.

## 4. Cấu trúc thư mục
- `data/`: Chứa dữ liệu thô và dữ liệu đã qua tiền xử lý.
- `src/`: Mã nguồn huấn luyện mô hình và xử lý dữ liệu.
- `docs/`: Tài liệu hướng dẫn cài đặt và báo cáo kỹ thuật.
- `results/`: Kết quả đánh giá mô hình, biểu đồ và log thực nghiệm.

## 5. Bản quyền & Giấy phép (License)
Dự án này được phát hành dưới giấy phép **MIT License**. Xem chi tiết tại tệp [LICENSE](./LICENSE).
