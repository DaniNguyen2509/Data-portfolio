# 📊 Maven Toys Data Sales Analysis

## 📝 Giới thiệu
**Maven Toys Data Sales Analysis** là dự án phân tích dữ liệu bán hàng của cửa hàng đồ chơi Maven Toys. Dự án sử dụng Python và SQL để xử lý dữ liệu từ nhiều nguồn, từ đó rút ra các insight quan trọng giúp tối ưu hóa chiến lược kinh doanh.

## 🎯 Mục tiêu dự án
- Phân tích doanh số bán hàng theo thời gian.
- Xác định sản phẩm bán chạy nhất.
- Đánh giá mức tồn kho và tối ưu hóa chuỗi cung ứng.
- Dự báo xu hướng bán hàng trong tương lai.
- Phân tích tác động của vị trí cửa hàng đến doanh thu.
- Đánh giá ưu nhược điểm của từng sản phẩm, danh mục sản phẩm dựa trên dữ liệu doanh số.

## 📂 Dữ liệu sử dụng
Dữ liệu được lưu trữ dưới dạng các file CSV:
- `sales.csv` - Dữ liệu bán hàng chi tiết.
- `products.csv` - Thông tin sản phẩm.
- `inventory.csv` - Số lượng hàng tồn kho.
- `stores.csv` - Dữ liệu về các địa điểm bán hàng.

## 🛠 Công nghệ & Công cụ
- **Ngôn ngữ lập trình:** Python, SQL (Google BigQuery)
- **Thư viện:** pandas, numpy, matplotlib, seaborn
- **Trực quan hóa:** Power BI / Tableau

## 📌 Các bước thực hiện
### 1️⃣ Data Cleaning & Preprocessing
- Kiểm tra dữ liệu bị thiếu hoặc sai lệch.
- Chuẩn hóa định dạng dữ liệu.

### 2️⃣ Exploratory Data Analysis (EDA)
- Phân tích tổng quan doanh số theo thời gian.
- Tìm ra nhóm sản phẩm bán chạy nhất.
- Phân tích mức tồn kho và doanh thu theo từng danh mục.
- Đánh giá tác động của vị trí cửa hàng đến doanh thu.
- Phân tích xu hướng doanh thu theo mùa vụ.
- Xác định ưu nhược điểm của từng sản phẩm dựa trên doanh số và xu hướng mua sắm từ khách hàng.

### 3️⃣ Trực quan hóa dữ liệu
- Sử dụng matplotlib & seaborn để vẽ biểu đồ xu hướng.
- Tạo dashboard trên Tableau.

📊 **Xem Dashboard Tableau tại đây:** [Maven Toys Tableau Dashboard](https://public.tableau.com/app/profile/thao.nguyen8096/viz/MavenToys3/DB3)

## 📊 Kết quả
- **Sản phẩm bán chạy nhất:** 🚀
- **Tháng có doanh số cao nhất:** 📈
- **Mức tồn kho cần tối ưu:** 📦
- **Địa điểm có doanh số cao nhất/thấp nhất:** 📍
- **Xu hướng doanh thu theo mùa vụ:** 📆
- **Ưu nhược điểm của từng dòng sản phẩm:** ✅❌

## 🚀 Hướng dẫn sử dụng
1. Clone repo này về máy:
   ```bash
   git clone https://github.com/DaniNguyen2509/Data-portfolio.git
   ```
2. Cài đặt thư viện cần thiết:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Chạy notebook Jupyter:
   ```bash
   jupyter notebook
   ```
4. Mở file `maven_toys.ipynb` và bắt đầu phân tích!

---
📌 **Liên hệ:** Nếu bạn có bất kỳ câu hỏi nào, hãy liên hệ qua [LinkedIn của tôi](https://www.linkedin.com/in/th%E1%BA%A3o-nguy%E1%BB%85n-16b7ba165/).
