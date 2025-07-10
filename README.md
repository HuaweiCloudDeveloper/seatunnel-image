<p align="center">
  <h1 align="center">SeaTunnel Distributed Data Integration Platform</h1>
  <p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction
[SeaTunnel](https://github.com/apache/seatunnel) is an easy-to-use, ultra-high-performance distributed data integration platform supporting real-time massive data synchronization.

**Why SeaTunnel?**  
SeaTunnel focuses on data integration and synchronization, addressing common challenges in the field:
- **Diverse Data Sources:** Hundreds of data sources with version incompatibilities. New sources emerge continuously, making it difficult for users to find a tool that comprehensively and quickly supports them.
- **Complex Synchronization Scenarios:** Requires support for offline full synchronization, offline incremental synchronization, CDC, real-time synchronization, full database synchronization, and more.
- **High Resource Requirements:** Existing tools often demand significant computing or JDBC connection resources for real-time synchronization of massive small tables, increasing enterprise burdens.
- **Lack of Quality and Monitoring:** Data loss or duplication frequently occurs during integration and synchronization. Monitoring is inadequate, making it hard to visualize real-time data status.
- **Complex Technology Stacks:** Enterprises use diverse technical components, necessitating custom synchronization programs for each, complicating development.
- **Difficult Management and Maintenance:** Offline and real-time synchronization often rely on different underlying technologies (Flink/Spark), requiring separate development and management.

This project provides the open-source image [**SeaTunnel**](https://marketplace.huaweicloud.com/hidden/contents/964ecab4-703f-40bd-b062-7961d3b866a1#productid=OFFI1148938068398186496), pre-installed with SeaTunnel and its runtime environment, along with deployment templates. Follow the guide to start your "out-of-the-box" experience!

> **System Requirements:**
> - CPU: 2GHz or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register for a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications

| Image Specification                  | Features Description                                        | Notes |
|-------------------------------------|------------------------------------------------------------|-------|
| [SeaTunnel-2.3.10-Kunpeng](https://github.com/HuaweiCloudDeveloper/seatunnel-image/tree/SeaTunnel-2.3.10-Kunpeng) | Installed and deployed on Kunpeng Server + Huawei Cloud EulerOS 2.0 64bit |       |

## Getting Help
- For more questions, contact us via [issues](https://github.com/HuaweiCloudDeveloper/seatunnel-image/issues) or the service support of the specified product on Huawei Cloud Marketplace.
- View other open-source images at [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit merge requests.
- Update README.md based on your open-source image information.
