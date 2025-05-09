# 🏖️ Leave Management System - Salesforce App

This is a mini Salesforce app for managing employee leave requests and balances. Built using Lightning Web Components, Apex, Flows, and custom metadata.

## 📦 Features

- Employees can apply for leave.
- Managers can approve/reject leave requests.
- Leave balances auto-update based on status.
- Team leave calendar with FullCalendar.js (LWC).
- Built-in dashboards and reports for HR.

## 🚀 Technologies Used

- Apex
- Lightning Web Components (LWC)
- Flows & Process Automation
- Custom Objects
- Experience Cloud (optional)
- Git + VS Code + Salesforce CLI

## 🛠️ Project Setup

```bash
sf project deploy start
```

## 📁 Folder Structure

```
force-app/
└── main/
    └── default/
        ├── classes/
        ├── lwc/
        ├── objects/
        ├── flows/
        └── dashboards/
```

## 💡 To Do

- [ ] Add `Leave_Request__c` and `Leave_Balance__c` objects
- [ ] Build LWC: ApplyLeaveForm
- [ ] Create auto-approval flow
- [ ] Add dashboards for leave status

---
**Author**: Olie
**License**: MIT