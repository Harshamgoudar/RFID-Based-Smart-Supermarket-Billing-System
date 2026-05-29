🛒 RFID-Based Smart Supermarket Billing System

📌 Overview

The RFID-Based Smart Supermarket Billing System is an embedded automation project developed using Raspberry Pi and RFID technology to automate supermarket billing and payment processing.

The system scans RFID-tagged products, displays item details, calculates the total amount automatically, and performs cashless payment verification using an RFID balance card.

This project demonstrates real-time billing automation using Embedded Systems, Raspberry Pi, and RFID-based authentication technology.

🚀 Features

✅ RFID-Based Product Scanning

✅ Automatic Bill Generation

✅ Quantity-Based Cost Calculation

✅ RFID Balance Card Payment

✅ Automatic Balance Deduction

✅ Insufficient Balance Detection

✅ Recharge / Top-Up Support

✅ Real-Time Billing System

✅ Cashless Supermarket Automation

🛠️ Technologies Used

Hardware Components

| Component                 | Purpose                   |
| ------------------------- | ------------------------- |
| Raspberry Pi              | Main Controller           |
| RFID Reader Module        | Product & Card Scanning   |
| RFID Product Tags         | Product Identification    |
| RFID Balance Card         | Cashless Payment          |
| LCD Display               | Billing Output            |
| Buzzer                    | Alert System              |
| Relay Module              | Optional Hardware Control |
| Breadboard & Jumper Wires | Connections               |

Software Used

* Python Programming
* GPIO Library
* Embedded Systems
* RFID Technology



🔷 Block Diagram
![Block Diagram](block_diagram.png)


⚙️ Working Principle

1. RFID reader scans the product tag.
2. Product details are identified from RFID data.
3. User enters quantity.
4. System calculates total amount automatically.
5. Total bill is displayed on LCD/output screen.
6. User taps RFID balance card for payment.
7. System checks available balance.
8. If balance is sufficient:

   * Amount is deducted automatically
   * Remaining balance is updated
   * Payment success message is displayed
9. If balance is insufficient:

   * System displays “Insufficient Balance”
   * User adds top-up balance
   * Updated balance is processed again

This creates a fully automated and cashless supermarket billing system.

📊 Results Obtained

* Accurate RFID product scanning achieved
* Automatic bill generation completed successfully
* Real-time payment processing implemented
* Balance deduction worked correctly
* Insufficient balance detection tested successfully
* Top-up balance update system verified
* Automated supermarket workflow demonstrated

🏭 Applications

* Smart Supermarkets
* Retail Automation
* Cashless Billing Systems
* Smart Shopping Systems
* Inventory & Billing Management

🔮 Future Enhancements

* Barcode Scanner Integration
* Mobile Payment Support
* IoT Cloud Monitoring
* Smart Cart Integration
* AI-Based Inventory Prediction
* Mobile App Billing System

📂 Repository Structure

```bash
RFID-Based-Smart-Supermarket-Billing-System/
│
├── README.md
├── smart_supermarket_billing.py
├── report.pdf
├── block_diagram.png
├── hardware_setup.png
└── output.png

👨‍💻 Developed By

Harsha Muttanna Goudar

BE – Electrical & Electronics Engineering
S.G. Balekundri Institute of Technology, Belagavi

📜 Internship Information

Developed during the Embedded Systems & IoT Internship at:

Loginware Softtec Pvt. Ltd.

⭐ Project Domain

Embedded Systems | RFID Technology | Raspberry Pi | IoT | Retail Automation
