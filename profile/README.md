
![LogiMaxx](logo_horizontal.png)


**LogiMaxx** is an IT services and tooling initiative focused on **monitoring**, **automation**, and **pragmatic software solutions** for technical teams.

The core philosophy is simple:  
**reduce manual work, increase visibility, and make systems predictable**.

---

## What We Do

### 🔍 Monitoring & Observability
- Zabbix consulting and implementation
- Large-scale environments (thousands of hosts, tags, templates)
- Migrations (Nagios, PRTG / legacy → Zabbix)
- SNMP, custom checks, APIs, and integrations
- Dashboarding and alerting strategies

### ⚙️ Automation
- Bulk operations via APIs (configuration, cleanup, migrations)
- Data transformation pipelines (CSV / Excel / API → system)
- Repeatable, auditable processes instead of one-off scripts

### 🧩 Custom Software
- Web-based internal tools
- Backend services and APIs
- Greenfield applications and system extensions
- Focus on **usefulness**, not overengineering

---

## Products & Tools

These tools are developed out of real operational needs and used in production.

### [**ZbxWizz**](https://github.com/logimaxx/zbxwizz)
A spreadsheet-like interface for working with the Zabbix API:
- Bulk host and tag management
- Import / export via CSV or Excel
- Transparent mass updates
- Reproducible operations (no hidden UI magic)

### **dbAPIator**
A dynamic Backend-as-a-Service layer:
- Automatically exposes a relational database as a REST API
- Adapts to schema changes
- JWT-based access control
- Event-driven architecture (Redis Streams)
- Designed for internal tools and fast iteration

> Products are intentionally pragmatic.  
> If a problem is better solved with a script or SQL, we do that.

---

## Tech Stack (Typical)

- **Monitoring**: Zabbix, SNMP, custom agents
- **Backend**: PHP, Node.js, MySQL
- **Frontend**: Vue / Nuxt
- **Infrastructure**: Docker, Linux, Nginx
- **Automation**: APIs, scripts, data pipelines
- **Storage & Messaging**: MinIO, Redis (Streams)

No vendor lock-in by default.

---

## How We Work

- Start from the **problem**, not the tool
- Prefer **simple, inspectable solutions**
- Automation must be **repeatable and explainable**
- Documentation is part of the deliverable
- No black boxes unless absolutely necessary

---

## Who This Is For

- Companies running **Zabbix at scale**
- Teams tired of fragile manual processes
- Organizations that need **custom internal tooling**
- Technical founders who want solutions, not slide decks

---

## Status

This repository serves as:
- A public entry point for LogiMaxx
- Documentation for tools and experiments
- A place to share reusable components and ideas

Some projects are open, others are client-specific.

---

## Contact

If you want to discuss:
- Monitoring architecture
- Automation strategies
- Custom tooling for operations

Open an issue or reach out directly.

---

**LogiMaxx**  
Monitoring. Automation. Control.
