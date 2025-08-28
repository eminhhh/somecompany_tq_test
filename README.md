# REPO for a question asked in a company's TQ

## General

This module allows you to list and manage users, including creating new ones.

It has two main sections:

1. **User Table** (left side)
2. **User Form (Edit/Create User)** (right side) 

## UI Components

### 1. Toolbar

**New User Button** (_+ New User_)

**Hide Disabled User Checkbox**: Change visibility of disabled users in the user table.

**Save User Button** (_Save User_)

### 2. User Table

A table which list users.

**Columns:**

- **ID**:  Auto-generated unique identifier
- **User Name**: Username of the account
- **Email**: Account’s email address
- **Enabled**: Status of account (`true` / `false`) 

**Features:**

- Sorting by name (by clicking on header)
- Filtering (by filter icons on header)

### 3. User Form (Edit/Create User)

**Fields:**

- **Username** (Text input, required)
- **Display Name** (Text input, optional)
- **Phone** (Text input, optional)
- **Email** (Text input, required, must be valid email format)
- **User Roles** (Dropdow, required, `Guest` / `Admin` / `SuperAdmin`)
- **Enabled** (Checkbox, default unchecked)

---

## Screenshot
![User Management UI](assets/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015.png)
