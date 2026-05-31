<div align="center">

# 📊 UNIACE WEBSITE TRAFFIC, SEO & USER JOURNEY ANALYTICS



![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue)
![DAX](https://img.shields.io/badge/DAX-Measures-orange)

</div>

### Phân tích Traffic Website • Hiệu quả SEO • Hành trình người dùng

**Tác giả**: Nguyễn Thị Ngọc Bích <br>
**Vai trò**: Data Analyst / Business Intelligence Portfolio Project <br>
**Công cụ sử dụng**: Excel, PostgreSQL, SQL, Power BI, DAX <br>
**Nguồn dữ liệu**: Dữ liệu Website Event của nền tảng giáo dục Uniace<br>
**Giai đoạn phân tích**: Tháng 01/2025 – Tháng 03/2025<br>

###  DASHBOARD TRỰC TUYẾN

<span align="left">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiN2NmYjY4YWYtOWQ3My00ODZhLWE1YTgtMWY1ZmM4OTdkNjRmIiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ%3D%3D&pageName=65362e4a0f9b81a0b882">
    🚀 View Interactive Power BI Dashboard
  </a>
</span>

## 📑 MỤC LỤC

* [📖 Giới thiệu dự án](#-giới-thiệu-dự-án)
* [🎯 Mục tiêu phân tích](#-mục-tiêu-phân-tích)
* [📊 Thông tin dự án](#-thông-tin-dự-án)
* [🛠️ Công nghệ sử dụng](#️-công-nghệ-sử-dụng)
* [🏗️ Kiến trúc giải pháp](#️-kiến-trúc-giải-pháp)
* [🔄 Quy trình xử lý dữ liệu](#-quy-trình-xử-lý-dữ-liệu)
* [📚 Data Dictionary](#-data-dictionary)
* [🗄️ Data Model](#️-data-model)
* [📈 KPI Framework](#-kpi-framework)
* [📊 Dashboard Walkthrough](#-dashboard-walkthrough)
* [💡 Key Insights](#-key-insights)
* [🚀 Business Recommendations](#-business-recommendations)
* [🎓 Skills Demonstrated](#-skills-demonstrated)
* [📂 Repository Structure](#-repository-structure)
* [📬 Contact](#-contact)

## 📖 GIỚI THIỆU DỰ ÁN
Uniace là nền tảng giáo dục trực tuyến cung cấp các khóa học và nội dung đào tạo về Excel, SQL, Power BI, Data Analytics và kỹ năng văn phòng. Website đóng vai trò là kênh thu hút người dùng thông qua SEO, Content Marketing và các nguồn traffic khác. Tuy nhiên, doanh nghiệp chưa có hệ thống phân tích tập trung để đánh giá hiệu quả hoạt động của website
Dự án được thực hiện nhằm xây dựng hệ thống phân tích **Traffic Website**, **SEO Performance** và **User Journey Analytics** cho nền tảng giáo dục Uniace.

Thông qua việc xử lý dữ liệu Website Event bằng PostgreSQL và xây dựng Dashboard trên Power BI, dự án giúp:

* Theo dõi hiệu quả thu hút người dùng
* Đánh giá chất lượng traffic từ SEO
* Phân tích hiệu suất nội dung (Content Performance)
* Phân tích hành trình người dùng (User Journey)
* Đánh giá khả năng chuyển đổi từ Content sang Course

# 🎯 MỤC TIÊU PHÂN TÍCH

Dashboard được xây dựng nhằm trả lời các câu hỏi kinh doanh:

* Website có bao nhiêu Users và Pageviews?
* Nguồn traffic nào mang lại hiệu quả cao nhất?
* SEO đóng góp bao nhiêu traffic?
* Nội dung nào thu hút nhiều người dùng nhất?
* Người dùng có chuyển từ Blog/Post sang Course hay không?
* Bước nào có tỷ lệ Drop-off cao nhất trong Funnel?
* Kênh nào mang lại người dùng có khả năng chuyển đổi cao?


## 📊 THÔNG TIN DỰ ÁN

| Hạng mục        | Thông tin               |
| --------------- | ----------------------- |
| Domain          | Education               |
| Industry        | EdTech                  |
| Analysis Type   | Website Analytics       |
| Analysis Period | 01/01/2025 - 31/03/2025 |
| Data Source     | Website Event Data      |
| Total Events    | 30,000+                 |
| Total Users     | 3,817                   |
| Main Tools      | PostgreSQL, Power BI    |


## 🛠️ CÔNG NGHỆ SỬ DỤNG

| Công cụ    | Vai trò                        |
| ---------- | ------------------------------ |
| Excel      | Nguồn dữ liệu gốc              |
| PostgreSQL | Lưu trữ và xử lý dữ liệu       |
| SQL        | Data Cleaning & Transformation |
| DBeaver    | Database Management            |
| Power BI   | Dashboard Development          |
| DAX        | KPI Calculation                |


## 🏗️ KIẾN TRÚC GIẢI PHÁP

```text

Raw Data
   ↓
Import to PostgreSQL
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Power BI Dashboard
```
<p align="center">
  <img src="Picture/Image May 27, 2026, 09_54_04 AM.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả kiến trúc xử lý dữ liệu</i>
</p>


## 🔄 QUY TRÌNH XỬ LÝ DỮ LIỆU

### Bước 1 — Raw Data Collection

Dữ liệu website được cung cấp dưới dạng Excel Raw Data.

Công việc thực hiện:

* Kiểm tra cấu trúc dữ liệu
* Kiểm tra kiểu dữ liệu
* Kiểm tra Missing Values
* Kiểm tra số lượng bản ghi

<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 014734.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả dữ liệu thô ban đầu </i>
</p>

---

### Bước 2 — Import PostgreSQL

Dữ liệu được import vào PostgreSQL thông qua DBeaver.

Công việc thực hiện:

* Import dữ liệu
* Tạo Staging Table
* Kiểm tra dữ liệu sau import

📌 **PostgreSQL Import Process**
<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 015916.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả dữ liệu bảng uniace khi import vào PostgreSQL  </i>
</p>

---

### Bước 3 — Data Cleaning

Các bước làm sạch dữ liệu:

| Task                | Description               |
| ------------------- | ------------------------- |
| Missing Values      | Xử lý dữ liệu thiếu       |
| Duplicate Records   | Loại bỏ dữ liệu trùng lặp |
| URL Standardization | Chuẩn hóa URL             |
| Datetime Formatting | Chuẩn hóa thời gian       |
| Event Validation    | Lọc valid pageview events |
<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 112356.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả kiểm tra trang account không còn bị nhầm lẫn sang Course </i>
</p>

---

### Bước 4 — Data Transformation

Tạo các trường phân tích:

* Traffic Source
* URL Type
* Is SEO
* Is Blog/Post
* Is Course
* Is Cart

Mục tiêu:

* Phân loại nguồn truy cập
* Phân loại loại trang
* Xây dựng logic SEO
* Hỗ trợ User Journey Analysis

<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 112625.png" width="90%">
</p>

<p align="center">
  <i>Hình ảnh phân loại nguồn truy  </i>
</p>

---

### Bước 5 — Dashboard Development

Kết nối Power BI với PostgreSQL và xây dựng Dashboard phục vụ:

* Traffic Analysis
* SEO Analysis
* Content Analysis
* User Journey Analysis
* Funnel Analysis


<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 112843.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh minh họa xu hướng Traffic Website theo thời gian và phân bổ người dùng theo nguồn truy cập, giúp đánh giá hiệu suất các kênh thu hút traffic và hành vi truy cập của người dùng trên website. </i>
</p>

## 📚 DATA DICTIONARY

Data Dictionary được xây dựng nhằm cung cấp tài liệu tham chiếu cho toàn bộ hệ thống dữ liệu.

Bao gồm:

* Table Definitions
* Column Descriptions
* KPI Definitions
* Business Rules
* Transformation Logic
* Traffic Source Logic
* URL Categorization Logic

> 📄 **Detailed Data Dictionary**  
> Tài liệu mô tả chi tiết các bảng dữ liệu, trường dữ liệu, business rules và KPI definitions.  
> 👉 [Download Excel File](Uniace_Data_Dictionary_Detailed.xlsx)



## 🗄️ DATA MODEL

### Data Model Overview

Mô hình dữ liệu được thiết kế theo kiến trúc Fact - Dimension nhằm tối ưu hiệu suất phân tích và hỗ trợ mở rộng Dashboard.

### Core Tables

| Table              | Type      |
| ------------------ | --------- |
| public_fact_events | Fact      |
| public_dim_user    | Dimension |
| public_dim_page    | Dimension |
| public_dim_source  | Dimension |

### Benefits

* Tối ưu hiệu suất Power BI
* Dễ xây dựng KPI
* Hỗ trợ SEO Analysis
* Hỗ trợ User Journey Analysis
* Dễ mở rộng dữ liệu

<p align="center">
  <img src="Picture/Image May 27, 2026, 10_23_04 AM.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả data model  </i>
</p>


## 📈 KPI FRAMEWORK

### Traffic KPIs

* Total Users
* Total Pageviews
* Pageviews / User

### SEO KPIs

* SEO Users
* SEO Share

### Content KPIs

* Blog Users
* Course Users
* Blog → Course Rate

### Conversion KPIs

* Cart Users
* Course Rate
<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-31 114508.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả các KPI được sử dụng trong báo cáo  </i>
</p>

## 📊 DASHBOARD WALKTHROUGH

### 1. Introduction

### Mục tiêu

Giới thiệu tổng quan về bài toán phân tích Website Traffic, SEO Performance và User Journey của Uniace.

Trang này giúp người xem hiểu nhanh:

- Bối cảnh dự án
- Mục tiêu phân tích
- Các nhóm insight chính
- Hướng đề xuất tối ưu dashboard

### Main Visuals

- Traffic Insight
- Content Insight
- User Journey Insight
- SEO Insight
- Recommendations

### Dashboard Preview
<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-29 232352.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh mô tả trang tổng quan của dự án  </i>
</p>


### 2️⃣ Content Performance

#### Mục tiêu

Đánh giá hiệu quả nội dung.

#### Main Visuals

* Top Content Pages
* Top SEO Pages
* Top Course Pages
* Content To Course Rate

<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-29 232233.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh đánh giá hiệu quả nội dung. </i>
</p>

### 3️⃣ User Journey Analysis

#### Mục tiêu

Phân tích hành trình người dùng.

#### Funnel Structure

```text
Total Users
      ↓
Blog/Post Users
      ↓
Course Users
      ↓
Cart Users
```
<p align="center">
  <img src="Picture/Ảnh chụp màn hình 2026-05-29 232332.png" width="100%">
</p>

<p align="center">
  <i>Hình ảnh phân tích hành trình người dùng.  </i>
</p>

## 💡 KEY INSIGHTS

### Traffic Insights

* Google là nguồn traffic lớn nhất.
* SEO đóng vai trò quan trọng trong việc thu hút người dùng mới.
* Direct Traffic cao cho thấy thương hiệu đã có mức độ nhận diện tốt.
* Internal Traffic phản ánh xu hướng khám phá nhiều nội dung trên website.

#### Content Insights

Các nhóm nội dung có hiệu suất cao:

* Excel
* SQL
* Power BI
* Data Analyst
* Young Talent Program

Tuy nhiên nhiều bài viết có lượng truy cập cao nhưng tỷ lệ chuyển đổi sang Course còn thấp.

#### Funnel Insights

Điểm Drop-off lớn nhất nằm ở:

```text
Blog/Post
     ↓
Course
```

Người dùng đọc nội dung nhưng chưa tiếp tục truy cập các trang khóa học.



## 🚀 BUSINESS RECOMMENDATIONS

### 1. Tối ưu CTA trong bài viết

* Thêm CTA rõ ràng
* Đặt CTA tại nhiều vị trí
* Tăng khả năng điều hướng sang Course

### 2. Tăng Internal Linking

* Liên kết các bài viết liên quan
* Liên kết nội dung với khóa học tương ứng

### 3. Tối ưu Landing Page khóa học

Làm rõ:

* Đối tượng học
* Nội dung học
* Kết quả đầu ra
* Dự án thực hành
* Học phí
* Hình thức học

### 4. Phát triển nhóm nội dung hiệu quả

Ưu tiên:

* Excel
* SQL
* Power BI
* Data Analyst
* Career Roadmap


## 🎓 SKILLS DEMONSTRATED

#### SQL & Database

✔ Data Cleaning

✔ Data Transformation

✔ PostgreSQL

✔ Data Validation

#### Power BI

✔ Data Modeling

✔ DAX Measures

✔ Dashboard Design

✔ Data Visualization

#### Analytics

✔ Traffic Analysis

✔ SEO Analysis

✔ Funnel Analysis

✔ User Journey Analysis

#### Business Intelligence

✔ Insight Generation

✔ Data Storytelling

✔ Business Recommendation


## 📂 REPOSITORY STRUCTURE

```text
uniace-website-seo-user-journey-analysis/
│
├── README.md
├── data/
├── sql/
├── powerbi/
│   └── Uniace_Website_Analytics.pbix
│
├── report/
│   └── Uniace_Analytics_Report.pdf
│
├── docs/
│   └── Uniace_Data_Dictionary.xlsx
│
└── Picture/
```


## 📬 CONTACT

**Nguyễn Thị Ngọc Bích**

Data Analyst | Business Intelligence

📧 Email: [nguyenthingocbich552003@gmail.com](mailto:nguyenthingocbich552003@gmail.com)

🔗 GitHub: https://github.com/NgocBich204
