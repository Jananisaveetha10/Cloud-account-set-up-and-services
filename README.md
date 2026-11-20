# Exp No. 1 : AWS Cloud Account Set up Root and IAM Access

## **Name:** JANANI S

## **Register Number:** 212224040127

---

# Aim

To create a cloud account in Amazon Web Services (AWS) and explore the various cloud services available in the AWS Management Console.

---

# Title

Introduction to AWS Identity and Access Management (IAM)

---

# Objective

The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

---

# Prerequisites

- Basic understanding of cloud computing concepts
- AWS Academy Lab access
- Web browser with internet connectivity

---

# Tools Used

- AWS Management Console
- AWS Identity and Access Management (IAM)
- Amazon EC2
- Amazon S3

---

# Tasks Performed

## Task 1: Explore IAM Users and Groups

- Reviewed pre-created IAM users:
  - user-1
  - user-2
  - user-3
- Explored IAM groups:
  - EC2-Admin
  - EC2-Support
  - S3-Support
- Inspected managed and inline policies attached to groups.

### Screenshot

<img width="1917" height="948" alt="image" src="https://github.com/user-attachments/assets/021c30ff-f6dd-4df9-b6b0-da8a046f1226" />


## Task 2: Add Users to Groups

Assigned IAM users to their respective groups based on organizational roles.

- Added **user-1** to the **S3-Support** group.
- Added **user-2** to the **EC2-Support** group.
- Added **user-3** to the **EC2-Admin** group.

This ensures that each user inherits the permissions associated with their assigned group, following AWS IAM best practices for role-based access control (RBAC).

### Screenshot

<img width="1916" height="995" alt="image" src="https://github.com/user-attachments/assets/eb4106ed-fb42-4ac4-9fc0-bbfa61f39884" />

<img width="1917" height="1005" alt="image" src="https://github.com/user-attachments/assets/c2f27d3f-ed54-4fab-8f81-0dacc074600f" />

<img width="1917" height="991" alt="image" src="https://github.com/user-attachments/assets/d39dc9b1-9356-4bba-b207-b4a6871618cb" />

## Task 3: Test IAM User Permissions

Validated IAM user permissions by signing in with the AWS IAM Sign-In URL and testing access to AWS services based on the assigned IAM group permissions.

- Logged in using the **AWS IAM Sign-In URL** with different IAM user accounts.
- Verified **Amazon S3** access for **user-1** (member of the **S3-Support** group).
- Verified **read-only access** to **Amazon EC2** for **user-2** (member of the **EC2-Support** group).
- Verified **administrative access** to **Amazon EC2** for **user-3** (member of the **EC2-Admin** group).

 ### Screenshot

<img width="1910" height="1057" alt="image" src="https://github.com/user-attachments/assets/6d01461f-be9f-4844-99e3-9da66a5ba19a" />

<img width="1916" height="1042" alt="image" src="https://github.com/user-attachments/assets/893bb15a-c977-4d2f-ba65-a84155729799" />

<img width="1892" height="1036" alt="image" src="https://github.com/user-attachments/assets/a859c1aa-3079-48a8-9551-6cc25ee1d5eb" />

The results confirmed that each user could access only the AWS resources and actions permitted by the IAM policies attached to their respective groups.

# Result

Thus, an AWS Cloud Account was created successfully, the account was secured using Multi-Factor Authentication (MFA), an IAM administrative user was configured, and the AWS Management Console along with its cloud services was explored successfully.

