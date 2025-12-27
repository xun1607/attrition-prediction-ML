# GCI Global 2025 - Final Assignment: Data-Driven Business Proposal

## 📖 Giới thiệu (Overview)
Kho lưu trữ này chứa mã nguồn và tài liệu báo cáo cho bài tập cuối khóa (**Final Assignment**) của chương trình **GCI Global 2025**. 

Dự án này là một Proof of Concept (PoC) mô phỏng vai trò của một chuyên viên tư vấn IT, nhằm giải quyết bài toán kinh doanh thực tế cho khách hàng thông qua phân tích dữ liệu (EDA) và Machine Learning.

## 🎯 Bối cảnh & Mục tiêu (Scenario & Objective)

**Bối cảnh:**
Đóng vai trò là một cộng sự (Associate) tại một công ty tư vấn IT. Nhóm kinh doanh vừa đạt được thỏa thuận PoC với một khách hàng sở hữu tập dữ liệu lớn nhưng chưa có chuyên môn nội bộ để khai thác.

**Mục tiêu dự án:**
1.  **Phân tích dữ liệu (EDA):** Tìm ra các vấn đề cốt lõi (pain points) và insight từ dữ liệu nội bộ kết hợp với phân tích thị trường bên ngoài.
2.  **Xây dựng mô hình Machine Learning:** Phát triển ít nhất một mô hình để giải quyết vấn đề đã xác định (có đánh giá Metric và Score cụ thể).
3.  **Đề xuất kinh doanh (Business Proposal):** Đưa ra giải pháp dựa trên dữ liệu với các tác động được định lượng rõ ràng (tăng doanh thu, giảm chi phí, giảm thiểu rủi ro,...).

## 📂 Cấu trúc thư mục (Repository Structure)
├── slides/ │
└── [Tên_Account_Omnicampus].pdf # Slide thuyết trình (Business Proposal) 
├── notebooks/ 
│ └── [Tên_Account_Omnicampus].ipynb # Source code phân tích và mô hình hóa 
└── README.md # Tài liệu hướng dẫn này

## 🛠️ Quy trình thực hiện (Workflow)

Dự án được thực hiện theo quy trình chuẩn của một dự án Data Science:

1.  **Market Analysis & Problem Definition:**
    * Nghiên cứu xu hướng thị trường (sử dụng dữ liệu bên ngoài).
    * Xác định mục tiêu kinh doanh và tác vụ ML phù hợp.
2.  **Exploratory Data Analysis (EDA):**
    * Trực quan hóa dữ liệu để tìm ra các mẫu (patterns) và ngoại lai (outliers).
    * Xây dựng giả thuyết về vấn đề của khách hàng.
3.  **Feature Engineering & Modeling:**
    * Xử lý dữ liệu và tạo đặc trưng mới.
    * Lựa chọn và huấn luyện mô hình (Model Selection).
4.  **Evaluation & Business Translation:**
    * Đánh giá mô hình dựa trên Metric kỹ thuật (Accuracy, RMSE, F1-Score,...).
    * Chuyển đổi kết quả kỹ thuật thành giá trị kinh doanh (Business Impact).

## 📊 Kết quả nổi bật (Key Results)

* **Mô hình sử dụng:** [Ví dụ: Random Forest / XGBoost / Logistic Regression]
* **Chỉ số đánh giá (Evaluation Metric):** [Ví dụ: AUC = 0.85, RMSE = 1200]
* **Tác động kinh doanh ước tính:**
    * [Ví dụ: Dự kiến giảm 15% tỷ lệ khách hàng rời bỏ (Churn Rate)]
    * [Ví dụ: Tối ưu hóa chi phí vận hành lên tới $50,000/năm]

*(Lưu ý: Chi tiết về quy trình phân tích và code vui lòng xem trong thư mục `notebooks`)*

## 🔧 Công nghệ sử dụng (Tech Stack)
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
* **Tools:** Jupyter Notebook, [PowerPoint/Canva/Figma cho Slide].

---
*Project by: [Xuan Nguyen]
