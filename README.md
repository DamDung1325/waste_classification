# Waste Classifier by Pictures 
This project focuses on building a deep learning model to classify waste images into different categories based on visual features. The goal is to support waste sorting and raise awareness of environmental protection through computer vision techniques.
The model is trained using a convolutional neural network (CNN) and can predict the waste type directly from an input image. This repository contains the training code, evaluation notebook, and the trained model weights for inference.
The project is implemented using Python and TensorFlow/Keras, and is suitable for educational and experimental purposes.
# Dataset:
the data used for this is kind of large, you can take a look by going into this URL: https://drive.google.com/drive/folders/1xL65-yZRKY7wDhLPq9fzD3UIh6t5Gvqn?usp=drive_link.
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
Upload hình ảnh lên Colab: Bạn có thể kéo thả hình ảnh vào phần tệp của Colab hoặc mount Google Drive và đặt hình ảnh vào đó.
Đường dẫn hình ảnh: Đặt đường dẫn chính xác đến hình ảnh của bạn.
Tiền xử lý hình ảnh: Mô hình của bạn mong đợi đầu vào có kích thước 224x224 pixel và được chuẩn hóa theo cách của EfficientNet. Chúng ta cần resize và tiền xử lý hình ảnh cho phù hợp.
Dự đoán: Sử dụng mô hình đã tải để đưa ra dự đoán.
Hiển thị kết quả: Hiển thị hình ảnh và kết quả dự đoán.
# Result:
Test Accuracy: 96.18%

