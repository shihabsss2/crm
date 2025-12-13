# [crm]  https://crmtooldemo.vercel.app

# 🚀 LeadFlow CRM

A modern, full-featured Customer Relationship Management system built with Next.js and MySQL.

**Live Demo:** [https://crmtooldemo.vercel.app](https://crmtooldemo.vercel.app)

## ✨ Features

### 👥 Customer Management
- Add, Edit, View, Delete customers
- Quick status update from table
- Customer fields: Name, Phone, Address, Lead Source, Potential Level, Status, Follow-up Date, Notes
- Status options: Follow Up, Interested, Converted, Not Interested, Not Answered, Do Not Disturb
- Potential levels: High, Medium, Low
- Lead sources: Social Media, Reference, Our End, Website, Other

### 🔐 User Authentication & Roles
- Login system with User ID and Password
- Two roles: Admin and User
- Users can only edit/delete their own customers
- Session tracking with login/logout times

### 📊 Dashboard & Statistics
- Real-time stats: Total Customers, Follow Up, Interested, Converted
- My List / All Customers toggle
- Stats change based on selected view (My List shows user's stats, All shows total)

### 🔍 Search & Filter
- Search by name, phone, address
- Filter by status
- Filter by potential level
- Pagination (25 per page)

### 📥 Bulk Import
- Import customers from CSV files
- Import customers from Excel files (.xlsx, .xls)

### 📤 Export
- Export to Excel (.xlsx)
- Export selected rows or all data
- Export only available in My List mode

### ⚠️ Duplicate Detection
- Warns when adding duplicate phone numbers
- Shows existing customer name and owner

### 🗑️ Delete Request System
- Users request deletion (soft delete)
- Admin approves or rejects delete requests
- Deleted rows show overlay with "Deleted by username"
- Users can undo their own delete requests

### 👑 Admin Panel
- User management (Add, Edit, Delete users)
- View all users with their stats
- Performance tracking (conversion rates)
- User customer list view
- User activity log (ADD, EDIT, DELETE, STATUS changes)
- Delete request approval system

### 🟢 Login Tracker
- Track who is online/away/offline
- Login and logout time tracking
- Session duration calculation
- Filter by date and user
- Total online time statistics

### 📈 Reports & Analytics (Admin)
- Pie charts: Status distribution, Potential levels
- Bar charts: Lead sources, User comparison
- Line chart: 30-day trend
- Date filters: Today, Last 7 Days, Last 30 Days, Custom Range

## 🛠️ Tech Stack

- **Frontend:** Next.js 14, React
- **Backend:** Next.js API Routes
- **Database:** MySQL
- **Charts:** Recharts
- **Export:** XLSX, PapaParse
- **Hosting:** Vercel



### User Dashboard
- Clean, modern UI with gradient header
- Quick stats cards
- Customer table with inline status update

### Admin Panel
- User management
- Performance metrics
- Login tracker
- Delete request management

## 👤 Default Credentials

| Role | User ID | Password |
|------|---------|----------|
| Admin | admin | 1234      |
| user  | shihab| 1234      |

## 📄 License

getwaybd

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

Built with ❤️ shihabhossain.online
