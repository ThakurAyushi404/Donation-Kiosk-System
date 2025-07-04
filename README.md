# 🙏 Donation Kiosk System – Contactless Giving with QR Receipts

This project showcases a **smart donation kiosk system** built for seamless, paper-free, and secure donations. Designed to operate autonomously in public spaces, this system supports **manual amount entry**, **custom descriptions**, and **email receipts**—making it ideal for **NGOs, churches, temples, gurdwaras**, and other donation-driven venues.

> 🚫 The full codebase is part of a commercial product and not published here. This repo provides **only visuals and selected sample code** for educational and presentation purposes.

---

## 💡 Key Features

- 💵 **Enter Manual Amount**  
  Donors can enter any custom donation amount on screen

- 📝 **Add Description & Phone Number**  
  Helps donors add purpose (e.g., "Education Fund", "Temple Renovation")

- 📩 **Get Receipt via QR or Email**  
  Paperless option with **QR-code receipt** and **email confirmation**

- 🙏 **Anonymous Donations Supported**  
  Users can choose to skip personal details

- 🧾 **Self Checkout & Payment Integrated**  
  Fast, contactless, and secure EFTPOS integration

- ⚙️ **Built with Advanced JavaScript, ASP.NET Core & Razor**  
  Smooth UX, responsive UI, and backend integration

---

## 🖥️ Screenshots

<p align="center">
  <img src="Donation-kiosk\donation.png" width="300"/>
  <img src="Donation-kiosk\Number pad.png" width="300"/>
  <img src="Donation-kiosk\QR.png" width="300"/>
</p>

---

## 🛠️ Tech Stack

- ASP.NET Core MVC + Web API
- Razor Views & jQuery
- SQL Server
- Azure Hosting
- Eftpos Payment Gateway
- DinkToPdf for QR Receipt Generation

---

## 🧪 Sample Code

```csharp
// Example donation model
public class MakeDonation
{
    public string KioskGuid { get; set; }
    public decimal Amount { get; set; }
    public string DonationDesc { get; set; }
    public string PhoneNumber { get; set; }
}
