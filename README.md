# 🐶 Dog NGO Website

A simple, responsive **Dog NGO Website** built using **HTML** and **CSS**, designed to raise awareness, showcase adoption drives, and collect donations securely using the **Razorpay Payment Gateway API**.

---

## 🌟 Features

- 🏠 **Home Page:** Clean and attractive landing section introducing the NGO’s mission.  
- 🐾 **About Section:** Information about the NGO’s vision, volunteers, and activities.  
- 🐕 **Adoption Section:** Showcases dogs available for adoption with their details.  
- 💸 **Donation Integration:** Secure online donation using the **Razorpay API**.  
- 📞 **Contact Section:** Contact form and NGO’s contact details.  
- 🌐 **Fully Responsive:** Works smoothly across mobile, tablet, and desktop devices.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Website structure |
| **CSS3** | Styling and responsiveness |
| **Razorpay API** | Payment gateway integration for donations |

---

## 💳 Razorpay Integration

The website includes a **Razorpay payment button** for secure donations.

### Example Integration:
```html
<form>
  <script 
    src="https://checkout.razorpay.com/v1/payment-button.js" 
    data-payment_button_id="YOUR_PAYMENT_BUTTON_ID" 
    async> 
  </script> 
</form>
