# SUBI LOGISTICS

Courier management and accounting software for a multi-branch courier agency
(ST Courier, Sri Maruthi, Garudavega International, Subi Travels).

## Status

This repository currently holds the **browser demo only**. It is not the production software.

- Data lives in the page and is lost on refresh.
- Demo passwords are plain text. Do not reuse real passwords.
- There is no server, database or backup.
- Do not put real customer or financial data in it.

## What the demo covers

Login with branch selection, dashboard (sample figures), branches, users and permissions,
customers, customer tariff (per-kg slabs and "Above" weight rates), destinations,
cash booking, RTO, Excel booking import, COD booking and delivery status,
invoices, and AWB stock (per branch and per customer). English and Tamil.

## Run the demo

Open `docs/index.html` in a browser. Excel import needs an internet connection.

Demo logins: `admin / admin123`, `stmanager / manager123`, `ststaff / staff123`.

## Files

- `docs/index.html`: page shell
- `docs/style.css`: styling
- `docs/app.js`: all screens and logic, in module order

## Publish the demo on GitHub Pages

Settings > Pages > Deploy from a branch > `main` and `/docs`.

## Planned production build

Node.js and Express backend, PostgreSQL database, secure role-based login with hashed passwords,
cloud file storage, and tested backup and restore. To be built phase by phase.
