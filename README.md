# Nguyễn Tấn Thành

Data Engineering Student | Building ETL/ELT Pipelines & Data Warehouses

---

## About

Sinh viên năm 4 chuyên ngành Data Engineering. Tập trung vào thiết kế data warehouse, xây dựng pipeline ETL/ELT và kiến trúc lakehouse xử lý cả dữ liệu batch lẫn streaming.

- Currently learning: Apache Spark, Kafka, Delta Lake, Prefect
- Interested in: Data Modeling (Kimball), Medallion Architecture, real-time data processing
- Looking for: Internship / Entry-level Data Engineer roles
- Contact: thanhnguyen108.online.2021@gmail.com

---

## Tech Stack

**Languages:** Python, SQL

**Data Engineering:** Apache Spark, Apache Kafka, SSIS, Delta Lake, Prefect

**Databases & Storage:** SQL Server, MinIO (S3-compatible), Trino

**Infrastructure:** Docker, Docker Compose

**BI & Visualization:** Power BI, Excel

---

## Featured Projects

### Real-Time Crypto Data Lakehouse
Hệ thống Data Lakehouse 5 lớp xử lý ~15GB dữ liệu Bitcoin lịch sử và luồng real-time từ Binance, theo kiến trúc Medallion (Bronze - Silver - Gold), sinh tín hiệu hỗ trợ giao dịch (Net Flow, VWAP, Whale Alert).

- Kiến trúc Lakehouse hợp nhất Batch + Streaming trên cùng một pipeline, không cần lớp Raw trung gian
- Delta Lake đảm bảo ACID transaction, schema evolution và time travel
- Điều phối bằng Prefect 2.x, đóng gói toàn bộ hạ tầng bằng Docker Compose
- Kết nối trực tiếp với Power BI qua REST API để trực quan hóa tín hiệu giao dịch

**Stack:** Apache Spark, Kafka, Delta Lake, MinIO, Prefect, Trino, Docker, Power BI

[View Repository](https://github.com/User-Name-netizen/crypto-market-signal-lakehouse)

---

### Olist E-Commerce Data Warehouse
Data warehouse phân tích thương mại điện tử theo mô hình Star Schema chuẩn Kimball, tự động hóa pipeline ETL bằng SQL Server Integration Services (SSIS), hợp nhất 9 file CSV (~1.5 triệu dòng) thành mô hình dữ liệu thống nhất.

- Thiết kế Star Schema với 6 Dimension và 4 Fact table, áp dụng Slowly Changing Dimension (Type 0/1/2)
- Pipeline ETL 17 Data Flow Task, có kiểm soát phụ thuộc (precedence constraint) và logging đầy đủ
- Tối ưu hiệu năng bằng Fast Load và giới hạn tập Lookup reference
- Phục vụ phân tích doanh thu, hiệu quả vận hành giao hàng, mức độ hài lòng khách hàng và hiệu suất seller

**Stack:** SQL Server, SSIS, Kimball Star Schema, SSMS, Power BI

[View Repository](https://github.com/User-Name-netizen/olist-data-warehouse-ssis)

---

## GitHub Stats

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=User-Name-netizen&show_icons=true&theme=default" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=User-Name-netizen&layout=compact" />
</p>

---

## Connect

LinkedIn: [tanthanh-nguyen-vn](https://www.linkedin.com/in/tanthanh-nguyen-vn/)
Email: thanhnguyen108.online.2021@gmail.com
