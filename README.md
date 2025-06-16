# E-Commerce Data Analytics Project
# Dự Án Phân Tích Dữ Liệu Thương Mại Điện Tử

## Project Overview | Tổng Quan Dự Án
This project focuses on analyzing e-commerce data to gain insights into sales performance, customer behavior, and market trends. The analysis is performed using Python with popular data science libraries.

Dự án này tập trung vào việc phân tích dữ liệu thương mại điện tử để hiểu rõ hơn về hiệu suất bán hàng, hành vi khách hàng và xu hướng thị trường. Phân tích được thực hiện bằng Python với các thư viện khoa học dữ liệu phổ biến.

## Data Files | Tệp Dữ Liệu
The project works with three main CSV files:
- `Sales target.csv`: Contains sales targets and actual performance data
- `List of Orders.csv`: Contains detailed order information
- `Order Details.csv`: Contains specific details about each order

Dự án làm việc với ba tệp CSV chính:
- `Sales target.csv`: Chứa dữ liệu về mục tiêu doanh số và hiệu suất thực tế
- `List of Orders.csv`: Chứa thông tin chi tiết về đơn hàng
- `Order Details.csv`: Chứa thông tin cụ thể về từng đơn hàng

## Data Preprocessing | Tiền Xử Lý Dữ Liệu
The data preprocessing steps include:
1. Handling missing values
2. Removing duplicates
3. Converting date formats
4. Splitting date columns into month and year
5. Addressing outliers in numerical columns

Các bước tiền xử lý dữ liệu bao gồm:
1. Xử lý giá trị thiếu
2. Loại bỏ dữ liệu trùng lặp
3. Chuyển đổi định dạng ngày tháng
4. Tách cột ngày thành tháng và năm
5. Xử lý các giá trị ngoại lai trong các cột số

## Analysis Results | Kết Quả Phân Tích
### Sales Target Analysis | Phân Tích Mục Tiêu Doanh Số
- Correlation analysis between different categories
- Identification of outliers in target values
- Monthly and yearly performance trends

### Order Analysis | Phân Tích Đơn Hàng
- Customer behavior patterns
- Product category performance
- Regional sales distribution

## Technologies Used | Công Nghệ Sử Dụng
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure | Cấu Trúc Dự Án
```
E-Commerce-Data-analytics/
├── data/
│   ├── Sales target.csv
│   ├── List of Orders.csv
│   └── Order Details.csv
├── notebooks/
│   └── E-Commerce-Data-analytics.ipynb
├── README.md
└── requirements.txt
```

## Getting Started | Bắt Đầu
1. Clone the repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook to view the analysis

## Future Improvements | Cải Tiến Trong Tương Lai
- Implement machine learning models for sales prediction
- Add more interactive visualizations
- Include real-time data analysis capabilities
- Develop a dashboard for monitoring key metrics

## Contact | Liên Hệ
For any questions or suggestions, please open an issue in the repository.

Để biết thêm thông tin hoặc góp ý, vui lòng tạo issue trong repository.