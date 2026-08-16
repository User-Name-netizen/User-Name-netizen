# Nguyễn Tấn Thành

**Data Engineering Student** | Building ETL/ELT Pipelines & Data Warehouses

<p align="left">
  <a href="https://www.linkedin.com/in/tanthanh-nguyen-vn/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:thanhnguyen108.online.2021@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/User-Name-netizen" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## About

Sinh viên năm 4 chuyên ngành Data Engineering. Tập trung vào thiết kế data warehouse, xây dựng pipeline ETL/ELT và kiến trúc lakehouse xử lý cả dữ liệu batch lẫn streaming.

- Currently learning: Apache Spark, Kafka, Delta Lake, Prefect
- Interested in: Data Modeling (Kimball), Medallion Architecture, real-time data processing
- Looking for: Internship / Entry-level Data Engineer roles

---

## Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,postgres,mssql,docker,git,powerbi&theme=dark" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/SSIS-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Prefect-1565C0?style=flat-square&logo=prefect&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" />
  <img src="https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white" />
</p>

---

## Featured Projects

### Real-Time Crypto Data Lakehouse

Hệ thống Data Lakehouse 5 lớp xử lý ~15GB dữ liệu Bitcoin lịch sử và luồng real-time từ Binance, theo kiến trúc Medallion (Bronze - Silver - Gold), sinh tín hiệu hỗ trợ giao dịch (Net Flow, VWAP, Whale Alert).

- Kiến trúc Lakehouse hợp nhất Batch + Streaming trên cùng một pipeline, không cần lớp Raw trung gian
- Delta Lake đảm bảo ACID transaction, schema evolution và time travel
- Điều phối bằng Prefect 2.x, đóng gói toàn bộ hạ tầng bằng Docker Compose
- Kết nối trực tiếp với Power BI qua REST API để trực quan hóa tín hiệu giao dịch

<p align="left">
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

**[View Repository](https://github.com/User-Name-netizen/crypto-market-signal-lakehouse)**

---

### Olist E-Commerce Data Warehouse

Data warehouse phân tích thương mại điện tử theo mô hình Star Schema chuẩn Kimball, tự động hóa pipeline ETL bằng SQL Server Integration Services (SSIS), hợp nhất 9 file CSV (~1.5 triệu dòng) thành mô hình dữ liệu thống nhất.

- Thiết kế Star Schema với 6 Dimension và 4 Fact table, áp dụng Slowly Changing Dimension (Type 0/1/2)
- Pipeline ETL 17 Data Flow Task, có kiểm soát phụ thuộc (precedence constraint) và logging đầy đủ
- Tối ưu hiệu năng bằng Fast Load và giới hạn tập Lookup reference
- Phục vụ phân tích doanh thu, hiệu quả vận hành giao hàng, mức độ hài lòng khách hàng và hiệu suất seller

<p align="left">
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/SSIS-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Star_Schema-FFB100?style=flat-square" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
</p>

**[View Repository](https://github.com/User-Name-netizen/olist-data-warehouse-ssis)**

---

## Connect

<p align="left">
  <a href="https://www.linkedin.com/in/tanthanh-nguyen-vn/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:thanhnguyen108.online.2021@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>
