# EliteTech_task-3
# ☁️ Task 3 – Multi-Cloud Architecture Design

## Cloud Computing Internship – ELiteTech Intern

This project demonstrates the design of a **Multi-Cloud Architecture** by integrating **Amazon Web Services (AWS)** and **Google Cloud Platform (GCP)**. The architecture highlights interoperability between cloud providers by using AWS for primary storage and Google Cloud for backup and analytics.

---

## 📌 Objective

Design a multi-cloud architecture utilizing AWS and Google Cloud services to improve scalability, availability, disaster recovery, and vendor independence.

---

## 🛠️ Cloud Services Used

### Amazon Web Services (AWS)
- Amazon S3 (Primary Storage)

### Google Cloud Platform (GCP)
- Google Cloud Storage (Backup Storage)
- BigQuery (Analytics - Conceptual)

---

## 🏗️ Architecture Overview

The architecture consists of:

- Users access the application.
- Files are stored in **Amazon S3**.
- Data is securely synchronized to **Google Cloud Storage**.
- BigQuery can be used to analyze stored data.
- The architecture improves reliability by distributing services across multiple cloud providers.

---

## 🚀 Implementation Steps

### Step 1
Created an **Amazon S3 Bucket**.

### Step 2
Uploaded `StudentData.csv` to the AWS S3 bucket.

### Step 3
Created a **Google Cloud Storage Bucket**.

### Step 4
Uploaded the same `StudentData.csv` to Google Cloud Storage.

### Step 5
Designed a Multi-Cloud Architecture diagram showing data flow between AWS and Google Cloud.

---

## 📂 Repository Structure

```
EliteTech_Task3/
│
├── README.md
├── Multi_Cloud_Architecture_Report.docx
├── architecture-diagram.png
└── Screenshot/
    ├── aws-s3-bucket.png
    ├── aws-file-upload.png
    ├── gcp-storage-bucket.png
    ├── gcp-file-upload.png
```

---

## 📸 Project Screenshots

### AWS S3 Bucket

Shows the primary storage bucket containing the uploaded file.

### Google Cloud Storage

Shows the backup bucket storing the same file.

### Multi-Cloud Architecture

Illustrates the interoperability between AWS and Google Cloud Platform.

---

## 📊 Features

- Multi-Cloud Architecture Design
- AWS S3 Primary Storage
- Google Cloud Storage Backup
- Cloud Interoperability
- Secure Data Flow
- High Availability
- Disaster Recovery
- Scalability

---

## 🎯 Benefits

- High Availability
- Vendor Independence
- Disaster Recovery
- Better Scalability
- Improved Reliability

---

## 📚 Skills Gained

- Multi-Cloud Architecture
- AWS S3
- Google Cloud Storage
- Cloud Interoperability
- Cloud Infrastructure Design
- Cloud Storage Management

---

## 📄 Report

The detailed project report is available in:

**Multi_Cloud_Architecture_Report.docx**

---

## 👨‍💻 Author

**Devi Sri Prasad Uddanti**

Cloud Computing Intern – ELiteTech Intern

---

## ⭐ Acknowledgement

This project was completed as part of the **Cloud Computing Internship** at **ELiteTech Intern**.
