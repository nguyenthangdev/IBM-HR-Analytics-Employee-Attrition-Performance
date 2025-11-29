# Intro AI Project

## Giới thiệu

Dự án dự báo khả năng nghỉ việc của nhân viên (Employee Attrition Prediction) tại công ty IBM.
Mục tiêu của dự án là sử dụng các mô hình Machine Learning để phân tích và dự đoán xem một nhân viên có khả năng nghỉ việc (Attrition) hay ở lại dựa trên các đặc điểm như:

- Tuổi, giới tính, lương, chức vụ
- Số năm kinh nghiệm, mức độ hài lòng, môi trường làm việc
- Khoảng cách từ nhà đến công ty, giờ làm việc, và nhiều yếu tố khác.

Dự án được xây dựng bằng Python, sử dụng `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `numpy` và các thư viện hỗ trợ khác để xử lý dữ liệu, huấn luyện mô hình và trực quan hóa kết quả.

---


## Cài đặt

### 1. Clone repository
```bash
git clone https://github.com/ThangNguyennv/IBM-HR-Analytics-Employee-Attrition-Performance.git
cd Project-Intro-AI
```

### 2. Tạo môi trường ảo
```bash
python -m venv venv
source venv/bin/activate    # Trên Linux/Mac
venv\Scripts\activate       # Trên Windows
```

### 3. Tạo môi trường 
```bash
pip install -r requirement.txt
```

### 4. Tải xuống Jupyter Notebook
```bash
sudo apt install jupyter-notebook # đối với Linux Ubuntu
```

### 5. Khởi chạy
```bash 
cd src
jupyter-notebook
```

## Các mô hình được sử dụng trong dự án

`Naive Bayes`, `Random Forest`, `Perceptron`

## Đánh giá mô hình

Các mô hình sẽ được đánh giá thông qua các chỉ số:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Nhóm tác giả:

| Họ và tên              | Vai trò     |  Email  |
| ---------------------- | ----------- | ------- |
| **Nguyễn Trung Thành** | Trưởng nhóm | ------- |
| **Nguyễn Văn Thắng**   | Thành viên  | ------- |       
| **Đinh Bá Thi**        | Thành viên  | ------- |
