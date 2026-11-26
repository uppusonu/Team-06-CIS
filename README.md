# 🚗 Smart Parking Space Detection System

### A Cloud-Based Approach to Identifying Vacant and Occupied Parking Spaces

## 📌 Project Overview

The **Smart Parking Space Detection System** is a camera-based solution designed to help drivers easily find available parking spaces.

A camera captures images of the parking area. An image-processing module analyses the parking slots and identifies each slot as either **VACANT** or **OCCUPIED**.

The latest parking information is stored using AWS cloud services and displayed through a simple web dashboard. Users can check parking availability without spending unnecessary time searching for an empty space.

## ❗ Problem Statement

In crowded places such as shopping malls, colleges and commercial buildings, drivers often spend a lot of time searching for available parking spaces.

This leads to:
- Wasted time searching for empty parking slots.
- Unnecessary vehicle movement.
- Increased congestion inside parking areas.
- Difficulty identifying vacant parking spaces.

Our project aims to solve these problems through automated parking-space detection.

## 🎯 Project Objectives

- Detect parking spaces using camera images.
- Identify each parking slot as vacant or occupied.
- Display available parking spaces through a web dashboard.
- Store parking information using AWS cloud services.
- Reduce the time spent searching for parking.
- Support multiple parking zones and cameras.
- Allow administrators to monitor parking information.

## ⚙️ System Workflow

Our system works in five steps:

1. **Capture:** A camera captures images of the parking area.
2. **Analyse:** The image-processing module analyses the marked parking slots.
3. **Classify:** Each parking slot is identified as VACANT or OCCUPIED.
4. **Update:** The latest parking information is sent to the cloud and stored.
5. **Display:** Users can view available parking spaces through a web dashboard.

## ☁️ AWS Services Used

We propose using the following eight AWS services:

| AWS Service | Purpose |
|---|---|
| Amazon S3 | Stores parking images and website files. |
| Amazon EC2 | Hosts the image-processing module. |
| AWS Lambda | Handles backend functions and updates parking information. |
| Amazon API Gateway | Connects the dashboard with the backend. |
| Amazon DynamoDB | Stores parking slot IDs, status and timestamps. |
| Amazon SNS | Sends parking availability notifications. |
| Amazon CloudWatch | Monitors application logs, errors and performance. |
| Amazon CloudFront | Delivers dashboard content to users. |

## 🏗️ Proposed System Architecture

```text
      PARKING CAMERA
             |
             v
       AMAZON EC2
    (Image Processing)
             |
             v
   API GATEWAY + LAMBDA
       (Backend)
             |
       +-----+-----+
       |           |
       v           v
   DYNAMODB       S3
 (Slot Status)  (Images)
       |
       v
   WEB DASHBOARD
       |
       v
  PARKING AVAILABILITY
   (VACANT / OCCUPIED)

 Additional AWS Services:
 SNS        - Notifications
 CloudWatch - Monitoring
 CloudFront - Dashboard Delivery
```

## 🌟 Expected Outcomes

- Easy identification of available parking spaces.
- Reduced time spent searching for parking.
- Less unnecessary vehicle movement.
- Better parking-space management.
- Real-time availability visibility based on the latest system updates.
- Flexibility to add more parking zones and cameras.

## 🛠️ Technologies and Tools

- **Cloud Platform:** Amazon Web Services (AWS)
- **Image Processing:** Camera-based image analysis
- **Backend:** AWS Lambda and Amazon EC2
- **Database:** Amazon DynamoDB
- **Storage:** Amazon S3
- **Dashboard:** Web-based application
- **Version Control:** Git and GitHub

## 👨‍💻 Team Members

**Team Number:** 6  
**Section:** 01

| S. No. | Team Member | Roll Number |
|---|---|---|
| 1 | Sujith | 2520030129 |
| 2 | U. Praneeth | 2520030188 |
| 3 | Varshith | 2520030598 |

## 👩‍🏫 Project Guide

**Harika Mam**  
Assistant Professor, Department of CSE

## 📚 Course Details

- **Course:** Cloud Infrastructure and Services
- **Course Code:** 25CS2206E
- **Academic Year:** 2026–2027
- **Institution:** KLH University

## 🔗 GitHub Repository

[Smart Parking Space Detection System – Team 06](https://github.com/uppusonu/Team-06-CIS)

---

### ✅ Conclusion

The Smart Parking Space Detection System aims to make parking easier, faster and more efficient using camera-based detection and AWS cloud technology. It helps drivers identify vacant parking spaces and supports better parking-facility management.

**Thank You!**
