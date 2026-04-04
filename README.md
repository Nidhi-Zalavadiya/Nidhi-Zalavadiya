<div align="center">

<!-- Visitor Counter -->
<img src="https://komarev.com/ghpvc/?username=Nidhi-Zalavadiya&style=flat-square&color=0F6E56&label=Profile+Views" alt="profile views"/>

<br/><br/>

<h1>Nidhi Zalavadiya</h1>
<h3>Python Developer · ERP Automation · GST Compliance Tech</h3>

<p>
  I turn hours of manual accounting work into seconds of automation.<br/>
  I build ERP integrations, GST compliance tools, and full-stack web apps that run in production at real accounting firms.
</p>

<!-- Tech Badges -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/XML_Processing-6A0DAD?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tally_ERP-FF6600?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tkinter-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenPyXL-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
</p>

<!-- Connect Badges -->
<p>
  <a href="https://linkedin.com/in/nidhizavalaiya">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:nidhizalavadiya2707@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Nidhi-Zalavadiya">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

</div>

---

## What I actually build

I work at the intersection of **Python automation** and **ERP systems**. Most of my tools solve real accounting pain — reading Government e-Invoice JSON, mapping GST tax data, and pushing the right vouchers into Tally automatically. If a workflow involves Excel, XML, or a REST API, I've probably automated it.

---

## Impact at a glance

| Metric | Result |
|--------|--------|
| Invoice processing time | 4 hours/day → under 60 seconds |
| Manual reconciliation eliminated | 2+ hours per week |
| Accounting firms using my tools | 3+ |
| Data-entry errors after automation | 0 |

---

## GitHub stats

<div align="center">

<!-- GitHub Stats + Streak side by side -->
<img height="170" src="https://github-readme-stats.vercel.app/api?username=Nidhi-Zalavadiya&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github"/>
&nbsp;&nbsp;
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=Nidhi-Zalavadiya&theme=tokyonight&hide_border=true"/>

<br/><br/>

<!-- Top Languages -->
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nidhi-Zalavadiya&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=c,c%2B%2B,cython"/>

</div>

---

## GitHub trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Nidhi-Zalavadiya&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7"/>
</div>

---

## Contribution activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Nidhi-Zalavadiya&theme=tokyo-night&hide_border=true&area=true&custom_title=Nidhi%27s%20Contribution%20Graph"/>
</div>

---

## Featured projects

### [EInvoice Pro — GST e-Invoice SaaS Platform](https://github.com/Nidhi-Zalavadiya/Tally_Automation)
> **Live · adopted by 3+ accounting firms**

Decodes Government e-Invoice IRN/JWT payloads and auto-pushes structured Purchase Vouchers into Tally ERP. Built a 3-step workflow (Upload → Map → Push) with persistent supplier-item mapping in PostgreSQL — repeat invoices from the same vendor need zero re-configuration.

**Stack:** FastAPI · Django · PostgreSQL · JWT · Tally ERP HTTP API  
**Impact:** 4 hours of daily invoice processing → under 60 seconds · zero manual data-entry errors

---

### [Bank Statement → Tally XML Converter](https://github.com/Nidhi-Zalavadiya/Tally_Automation)
> **In active daily production use**

Parses formatted Excel bank statements, fetches live Tally ledgers, generates import-ready XML vouchers, and auto-creates missing ledger entries under the correct groups — all from a desktop GUI.

**Stack:** Python · Tkinter · OpenPyXL · XML · Tally ERP HTTP API  
**Impact:** 2+ hours of daily reconciliation → under 5 minutes

---

### [Bulk Sales Voucher Generator](https://github.com/Nidhi-Zalavadiya/Final-Version-Bulk-Sales-Import-Without-Gst-Multiitems-and-Accounting-)
> **Adopted firm-wide within the first week**

GUI desktop tool that batch-generates ERP-compatible sales vouchers for direct Tally import — replacing 2+ hours of repetitive manual data entry per session.

**Stack:** Python · Tkinter · XML · Tally ERP  
**Impact:** Eliminated hours of labour-intensive input per session

---

### [Salon Management System — Full-Stack Web App](https://github.com/Nidhi-Zalavadiya/MMG)
> **6-module dual-portal platform**

Dual-portal web platform (Admin + Customer) featuring appointment scheduling, product e-commerce, membership tiers, inventory control, and anonymous feedback. Owned the full stack from schema design to UI delivery.

**Stack:** Django · JavaScript · AJAX · MySQL  
**Impact:** Supports 100+ concurrent bookings · reduces manual admin tasks by 70%

---

## A typical problem I solve

```python
# Before: an accountant's morning routine
open_government_portal()           # 15 min
download_einvoices()               # 10 min
manually_decode_irn_jwt()          # 45 min
cross_reference_hsn_gstin()        # 60 min
type_into_tally_one_by_one()       # 90 min
# total: ~4 hours, error-prone

# After: EInvoice Pro
einvoice_pro.process("invoice.json")   # < 60 seconds, zero errors
```

---

## Tech stack

| Area | Tools |
|------|-------|
| **Languages** | Python, JavaScript, SQL, HTML5, CSS3 |
| **Backend** | FastAPI, Django, Django REST Framework, REST APIs, JWT |
| **Frontend** | AJAX, HTML5, CSS3 |
| **Databases** | PostgreSQL, MySQL |
| **ERP & Gov Tech** | Tally ERP (HTTP/XML API), Government e-Invoice (IRN/JWT), GST Compliance (CGST/SGST/IGST) |
| **Desktop / Automation** | Tkinter, Kivy, OpenPyXL, XML Processing, Excel Automation |
| **Tools** | Git, Postman, VS Code |

---

## Education

**Bachelor of Computer Applications (BCA)**  
Chimanbhai Patel Institute of Computer Applications · Gujarat University · 2021–2024

---

<div align="center">

<!-- Snake contribution animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nidhi-Zalavadiya/Nidhi-Zalavadiya/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Nidhi-Zalavadiya/Nidhi-Zalavadiya/output/github-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/Nidhi-Zalavadiya/Nidhi-Zalavadiya/output/github-snake.svg"/>
</picture>

<br/>

*⭐ Star a repo if something here helped you!*

</div>
