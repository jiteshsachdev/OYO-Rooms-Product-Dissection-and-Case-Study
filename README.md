# OYO Rooms & Hotels — Product Dissection and Case Study

This repository contains a detailed product dissection, real-world problem analysis, and database schema design for **OYO Rooms & Hotels**, one of the world's largest hospitality platforms.

---

## 📌 Repository Headline (Use on GitHub)

**OYO Rooms – Product Dissection, Case Study & Database Schema Design**

---

## 📖 Project Overview

This project provides an in-depth analysis of how OYO Rooms solves real-world hospitality challenges using technology, standardisation, and customer‑centric design. It also includes a complete relational database schema with entities, attributes, and relationships used in hospitality systems.

---

## 🏨 Company Overview

OYO Rooms, founded in 2013 by Ritesh Agarwal, revolutionised budget travel by offering **standardised, affordable, and hygienic rooms**. Its platform connects travellers with verified hotels and homes across 80+ countries.

---

## 🎯 Objectives of the Project

* Analyse real-world travel and hotel problems
* Understand OYO’s tech-driven solutions
* Break down key product features
* Design a complete database schema
* Understand relationships between users, rooms, bookings & payments

---

## 🧩 Real-World Problems Solved by OYO

### **1️⃣ Budget-Friendly Accommodation**

Travellers previously struggled to find quality stays within budget.

* **OYO's Solution:** Standardised affordable rooms across cities.

### **2️⃣ Hygiene & Safety Concerns**

Post-COVID, cleanliness became a major concern.

* **Solution:** *Sanitised Stays* with strict safety protocols.

### **3️⃣ Last-Minute Booking Hassles**

Finding real-time availability was difficult.

* **Solution:** Instant booking with live availability on the app.

### **4️⃣ Trust Issues with Property Quality**

Online listings were often misleading.

* **Solution:** Verified hotels + authentic reviews.

### **5️⃣ Limited Payment Options**

Travellers needed flexible payments.

* **Solution:** Wallet, UPI, cards, net banking, offers.

---

## ⭐ Top Features of OYO Platform

* User Profiles
* Verified Property Listings
* Real-time Availability & Instant Booking
* Multiple Secure Payment Methods
* Reviews & Ratings
* Offers & Discounts
* Location-Based Search

---

## 🗂 Database Schema Overview

This schema models how OYO manages users, rooms, bookings, payments, and reviews.

### **Entities Included:**

* **User** (UserID, Name, Email, Phone, WalletBalance)
* **Hotel** (HotelID, Name, LocationID, Rating)
* **Room** (RoomID, HotelID, Type, Price, Availability)
* **Booking** (BookingID, UserID, RoomID, Dates, PaymentStatus)
* **Payment** (PaymentID, BookingID, Method, Amount)
* **Review** (ReviewID, BookingID, Rating, Comments)
* **Location** (LocationID, City, State, Country)
* **Offer** (OfferID, Discount, Validity, HotelID)

### **Key Relationships:**

* User → Books → Booking
* Booking → For → Room
* Room → Belongs to → Hotel
* Hotel → Located at → Location
* Booking → Has → Payment
* User → Leaves → Review
* Offer → Applies to → Hotel

---

## 🧾 ER Diagram (Conceptual Overview)

**User → Booking → Room → Hotel → Location → Offer**

**Booking → Payment**

**User → Review → Booking**

(You can add the image of the ER diagram when available.)

---

## 🎥 Video Demonstration

A complete walkthrough of this project is available here:

🔗 [https://drive.google.com/file/d/1nqyVYBOhGzhyUcHa-OrceYKm_vN2jkqm/view?usp=sharing](https://drive.google.com/file/d/1nqyVYBOhGzhyUcHa-OrceYKm_vN2jkqm/view?usp=sharing)

---

## 🏁 Conclusion

OYO’s tech platform solves key hospitality challenges—affordability, hygiene, trust, and convenience. Its database structure supports millions of bookings while maintaining accuracy and performance. This project provides a complete breakdown of how the system works from product and data perspectives.

---

## 👤 Author

**Jitesh Sachdev**

Feel free to contribute, suggest improvements, or connect for collaboration!
