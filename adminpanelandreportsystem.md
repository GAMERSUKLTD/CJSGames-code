# 🎮 F5 Player Report System + F1 Admin Panel

## 📌 Description

This script provides a complete in-game support system for your FiveM server, allowing players to easily contact staff while giving admins a dedicated control panel to manage incoming reports.

Players can open a clean and immersive report menu using the **F5 key**, while staff members with the correct permissions can access an **admin panel via F1** to view and respond to reports in real time.
(on the panels it will say "CJS Reports" as the name of the panel)
---

## ⚙️ Features

### 👤 Player Features (F5 Menu)

* 🖥️ Open report menu instantly using **F5**
* 📂 Multiple report categories:

  * Player Reports
  * Bug Reports
  * General Help
* 💬 Custom message input for detailed descriptions
* ✅ Confirmation when a report is submitted
* 🎯 Clean UI that improves roleplay immersion

---

### 🛠️ Admin Features (F1 Panel)

* 🔐 Access admin panel using **F1 key**
* 👮 Restricted to players with ACE permission:

  ```
  member
  ```
* 📋 View incoming reports in real time
* 📡 Receive instant notifications when a player submits a request
* ⚡ Quickly respond or take action on reports

---

## 🔐 Permissions Setup

Admins must have the following ACE permission to access the panel:

```
add_ace group.pier_member "pier.basic" allow
add_ace group.afl_member "afl.basic" allow
add_ace group.ah_member "ah.basic" allow
add_ace group.rec_member "rec.basic" allow
add_ace group.gangs_member "gangs.basic" allow
add_ace group.legal_member "legal.basic" allow
add_ace group.orgs_director "orgs.direct" allow
```

---

## 🎯 Purpose

This system replaces outdated chat commands with a modern interface, helping servers:

* Improve communication between players and staff
* Reduce chat spam
* Provide faster admin response times
* Enhance overall server professionalism

---

## 🛠️ Use Case

* A player presses **F5**, selects a category, and submits a report
* An admin presses **F1** to open the admin panel
* The report appears instantly, allowing staff to respond quickly

---

## 🚀 Optional Enhancements

* Discord webhook logging
* Report claim system (admins can take ownership of reports)
* Teleport-to-player feature
* Cooldown system to prevent spam
* Report history / ticket tracking

---

## 👤 Ideal For

* Serious RP servers
* Public servers with active moderation
* Communities looking for a clean and modern support system

---

## 📦 Summary

A complete player support solution combining an **F5 report menu** and an **F1 admin panel**, designed to streamline communication, improve response times, and elevate your server experience.
