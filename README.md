# Canteen-Management-System
## St. Xavier's Digital Canteen

A modern, browser-based canteen management and meal pre-ordering system built using **HTML**, **Tailwind CSS**, **JavaScript**, and **Firebase**.  
The application enables students to pre-order meals, track their orders, and view order history, while the canteen staff can monitor live orders, manage payment statuses, and track daily meal capacity.

---

## Features

### **Student Features**
- Secure login using roll number.
- View daily menu with item prices.
- Add items to cart and select pickup time slots.
- Place orders in real time.
- View complete order history with status and payment details.
- Alerts when meal capacity is reached.

### **Canteen Features**
- Login with secure credentials.
- View live order lists categorized by pickup time.
- Update order statuses (Confirmed → Ready → Delivered).
- Mark payments as Paid or Pending.
- Track total orders, collections, and pending dues.
- Monitor daily meal capacity with a visual progress bar.

---

## Technologies Used
- **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6 Modules)
- **Backend & Database:** Firebase Authentication, Firebase Firestore
- **Icons & Fonts:** Font Awesome, Google Fonts (Inter)
- **Hosting:** Any static site host (Firebase Hosting, Netlify, GitHub Pages)

---

## How It Works
1. **Authentication:**  
   - Students log in using their roll number.  
   - Canteen staff log in with predefined credentials.

2. **Ordering:**  
   - Menu is dynamically displayed with add-to-cart functionality.  
   - Orders are stored in Firestore with details like items, quantity, total, time slot, and status.

3. **Live Updates:**  
   - Real-time Firestore listeners update order history for students and live order lists for the canteen.

4. **Capacity Control:**  
   - The app tracks and limits meal orders to 200 per day.

---

## Setup Instructions
1. Clone the repository.
2. Replace the Firebase configuration in `index.html` with your project’s credentials.
3. Deploy to a static hosting platform or run locally by opening `index.html` in a browser.

---
## Login Details
### Student
- Any integer roll no.
### Admin 
- Username : chandrettan
- Password : canteen123


## Future Enhancements
- Add online payment integration.
- Enable menu management through an admin interface.
- Implement mobile app version for faster ordering.
- Add push notifications for order updates.

---

**Author:** Alen K Aji
