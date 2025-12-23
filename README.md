# Waste Classifier by Pictures 
Dự án này tập trung vào việc xây dựng một mô hình học sâu để phân loại rác thải từ hình ảnh thành các nhóm khác nhau dựa trên đặc trưng thị giác. Mục tiêu của dự án là hỗ trợ việc phân loại rác và nâng cao nhận thức về bảo vệ môi trường thông qua các kỹ thuật thị giác máy tính.
Dự án được triển khai bằng Python và TensorFlow/Keras, phù hợp cho mục đích học tập và nghiên cứu thử nghiệm.
# Dataset:
dữ liệu được sử dụng trong quá trình huấn luyện mô hình khá lớn nên bạn có thể tham khảo qua đường link sau: https://drive.google.com/drive/folders/1xL65-yZRKY7wDhLPq9fzD3UIh6t5Gvqn?usp=drive_link.
# Feature:
- Phân loại rác thải dựa trên hình ảnh đầu vào
- Nhận diện nhiều loại rác khác nhau bằng mô hình học sâu
- Cho phép sử dụng mô hình đã huấn luyện sẵn để dự đoán mà không cần huấn luyện lại
- Hỗ trợ quy trình dự đoán đơn giản, dễ sử dụng
- Có thể mở rộng và huấn luyện thêm với dữ liệu mới
# Installation:
Dự án được triển khai và chạy trực tiếp trên Google Colab, không yêu cầu cài đặt môi trường cục bộ.
# Usage:
Để thử nghiệm mô hình trên một hình ảnh tự chụp, bạn cần thực hiện các bước sau:
- Upload hình ảnh lên Colab: Bạn có thể kéo thả hình ảnh vào phần tệp của Colab hoặc mount Google Drive và đặt hình ảnh vào đó.
- Đường dẫn hình ảnh: Đặt đường dẫn chính xác đến hình ảnh của bạn.
- Tiền xử lý hình ảnh: Mô hình của bạn mong đợi đầu vào có kích thước 224x224 pixel và được chuẩn hóa theo cách của EfficientNet. Chúng ta cần resize và tiền xử lý hình ảnh cho phù hợp.
Dự đoán: Sử dụng mô hình đã tải để đưa ra dự đoán của mô hình.
Hiển thị kết quả: Hiển thị hình ảnh và kết quả dự đoán của mô hình.
# Result:
Kết quả của mô hình sau khi train với dataset: Accuracy: 96.18%

