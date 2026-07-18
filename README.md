# hospitalsite
# 🏥 Shusruta-Samita Hospital — Online Appointment Booking

A mini-project built to digitize the hospital's appointment process — patients can browse doctors, view their profiles, and book an appointment online instead of standing in a physical queue.

## 📖 About

This is a basic **dynamic front-end website** for **Shusruta-Samita Hospital, Dumka, Jharkhand**, created to save patients' time by moving appointment registration online.

## ✨ Features

- **Home Page** — Hospital intro, scrolling welcome marquee, navigation to Services/Doctors/Contact
- **Doctor Listings** — Displays available doctors with photo, name, and specialty
- **Doctor Profile Pages** — Individual profile per doctor with specialty, experience, and address
- **Appointment Booking Form** — Collects patient details (name, father's name, mobile, email)
- **Payment Simulation** — Multiple payment method options (Card / UPI / Net Banking) with dynamic form fields and a processing screen
- **Payment Success Page** — Confirmation screen with auto-generated transaction ID and date
- **Contact Form** — Standalone page for general inquiries
- **Customer Testimonials** — Expandable "View All" reviews section
- **Responsive Styling** — Custom CSS with gradients, hover animations, and Tailwind CSS (on form pages)

## 🛠️ Tech Stack

- **HTML5** — Page structure
- **CSS3** — Custom styling, gradients, animations, media queries
- **Tailwind CSS (CDN)** — Used on payment & success pages
- **JavaScript (Vanilla)** — Toggle reviews, dynamic payment fields, form submission handling
- **Font Awesome** — Icons for the services section

## 📂 Project Structure

```
HospitalSite/
├── index.html              # Homepage
├── project2.css            # Homepage styling
├── doc1.html                # Doctor profile - Dr. MK Pandit
├── doc2.html                # Doctor profile - Dr. Smriti Sah
├── doc3.html                # Doctor profile - Dr. Mukesh Verma
├── doc1.css                 # Shared doctor profile styling
├── payment_form.html        # Appointment & payment form
├── finish.html               # Payment success page
├── contactform.html          # Contact form
├── contactform.css           # Contact form styling
├── style1.css                # Misc styling
└── images/                   # Doctor photos & hospital banner
```

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/ankitkr-code/hospitalsite
   ```
2. Open `index.html` in your browser — no build step or server required.

## 📝 Notes / Known Limitations

- This is a **front-end only prototype** — the payment gateway is simulated (no real transaction processing or backend integration yet).
- The appointment form does not currently persist data to a database.
- Built as a learning/mini-project to practice HTML, CSS, and JS fundamentals alongside Tailwind.

## 🔮 Future Improvements

- Connect to a real backend (Node/Express + database) to store appointments
- Integrate an actual payment gateway (Razorpay/Stripe)
- Add doctor availability & time-slot selection
- Add admin panel for managing doctors and appointments

## 👤 Author

Ankit — CSE student, building full-stack projects with a focus on shipping working products.
