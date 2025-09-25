# 🔗 IBM MQ User Tracker API  
_.NET Web API for User Tracking on IBM MQ Servers_  

---

## 📖 Overview  
The **IBM MQ User Tracker API** is a lightweight **.NET Web API** solution developed for a **confidential client (UAB Bank, Middle East)**.  
It integrates with **IBM MQ servers** to monitor and track **user logins** across systems, enabling better **auditability, compliance, and security visibility**.  

---

## 🚀 Features  
- ✅ **Real-time user tracking** from IBM MQ queues  
- ✅ RESTful **.NET Web API endpoints** for easy integration  
- ✅ Secure and configurable **connection to MQ servers**  
- ✅ Provides **audit logs** for login activities  
- ✅ Simplified administration & monitoring of active users  

---

## 🛠️ Tech Stack  
- **Framework**: .NET Web API (C#)  
- **Middleware**: IBM MQ  
- **Integration**: MQ Client libraries  
- **Architecture**: RESTful API  

---

## ⚙️ How It Works  
1. The API connects to the **IBM MQ queue manager** using provided credentials.  
2. Listens for **login events** published to specific MQ queues.  
3. Extracts user session metadata (user ID, timestamp, system ID).  
4. Exposes data through **Web API endpoints** for reporting & monitoring.  
