---
marp: true
theme: default
paginate: true
---

# 🔥 Firewall as a Service (FWaaS)

Η Πρώτη Γραμμή Άμυνάς σας στον Ψηφιακό Κόσμο

---

## 📋 Λόγοι σχεδίασης της λύσης

- Κεντρική, διαχειριζόμενη υπηρεσία ασφάλειας για όλους τους φορείς
- Χωρίς ανάγκη επένδυσης σε τοπικό εξοπλισμό ασφαλείας
- Δεν απαιτείται εξειδικευμένο προσωπικό
- Υψηλή διαθεσιμότητα μέσω γεωγραφικής κατανομής
- Κεντρική διαχείριση μέσω **FortiManager**
- Monitoring & Reporting μέσω **FortiAnalyzer**
- **Managed Service μοντέλο**: Ασφάλεια χωρίς κόπο
- Ευελιξία & επεκτασιμότητα

---

## 🖥️ Οικοσύστημα υποδομής

- 2 x FortiGate 5144C chassis
- 4 x FortiGate 5001D blades (Active-Standby)
- FortiManager VM
- FortiAnalyzer VM

---

## 🔐 Χαρακτηριστικά υπηρεσίας

- Stateful Firewalling
- IPS (Intrusion Prevention System)
- DoS/DDoS Mitigation
- Anti-Malware/Antivirus
- Application Control
- Static URL Filtering
- VPN Remote Access
- Data Loss Prevention (DLP)

---

## 📝 Παράδοση υπηρεσίας

1️⃣ Αίτημα ➔ ΕΔΥΤΕ  
2️⃣ Δημιουργία Virtual Firewall (VDOM)  
3️⃣ Σύνδεση μέσω FortiManager (Radius Auth)  
4️⃣ Διαχείριση πολιτικών από φορέα  
5️⃣ Monitoring μέσω FortiAnalyzer

---

## ⚙️ FortiManager

- **Policy & Objects**: Διαχείριση πολιτικών
- **VPN Manager**: Διαχείριση VPN
- **Fabric View**: Απεικόνιση δικτύου

---

## 📊 FortiAnalyzer

- SOC δυνατότητες
- Πλήρης ανάλυση logs
- Παρακολούθηση Incidents & Events
- Advanced reporting

---

## 🖧 Τοπολογία

CE Router ➔ PE Router ➔ FortiGate Firewall ➔ Internet

- Υποστήριξη inside/outside zones ανά φορέα
- BGP peering
- VRFs ανά οργανισμό

---

## 🚀 Closing

Η λύση **FWaaS του ΕΔΥΤΕ** προσφέρει:

✅ Ασφάλεια  
✅ Διαθεσιμότητα  
✅ Ευκολία & απλοποίηση διαχείρισης  
✅ Χωρίς επιπλέον κόστος ή προσπάθεια από τους φορείς
