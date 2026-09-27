<img src="assets/header.svg" width="100%" alt="Hekimcan Aktaş — Cloud & Database Engineer"/>

I build software end to end, from the interface down to the database, mostly with **.NET, Oracle and PL/SQL**. The parts I care about most are the ones that are hard to see: transaction boundaries, how data is stored, who is allowed to read it, and what trail it leaves behind.

I'm Oracle Cloud Infrastructure certified and currently **open to remote roles** in cloud, database, data engineering or full stack .NET — full-time or contract, from İzmir (UTC+3), fully overlapping with European working hours.

<br/>

## Experience

**Probel Yazılım** — Software Engineer (Intern)<br/>
<sub>Jun 2026 – Sep 2026 · İzmir</sub>

As part of the internship, I built a patient feedback and service recovery module end to end for an enterprise hospital information system. Surveys go out automatically, responses are scored with NPS, CSAT and CES, and low scores open a case that staff track on a dashboard. Clinical events are verified with HMAC signatures, invitations go out over WhatsApp and SMS, and personal data is encrypted, audit-logged and retained under GDPR and KVKK rules. On the database side I wrote the PL/SQL procedures, tuned the queries and ran Oracle locally on Docker.

<sub>.NET 8 · ASP.NET Core MVC · Dapper · Oracle · PL/SQL · DevExpress · DevExtreme · SignalR</sub>

**Freelance** — Software Developer<br/>
<sub>2023 – May 2026</sub>

Two restaurant billing and POS systems and two QR menu and ordering systems, each delivered end to end to a paying client. One of the ordering systems accepts orders only from inside the venue, using a PostGIS geofence, and a small Node.js agent routes each order to the kitchen's thermal printer.

<sub>.NET · SQL Server · Node.js · PostgreSQL · PostGIS</sub>

<br/>

## Projects

**Double-entry ledger and reconciliation engine**<br/>
A ledger whose balance cannot drift and where a resubmitted transaction is never posted twice. At the end of each day it matches entries against card, EFT and correspondent files and produces a discrepancy report. Most of the work is in transaction isolation, locking and exactly-once processing.<br/>
<sub>PostgreSQL · .NET</sub>

**MEDULA invoice pre-check and rejection prevention engine**<br/>
Runs SUT reimbursement rules against a healthcare invoice before it is submitted, flags the records that would be rejected and proposes a correction for each.<br/>
<sub>.NET · Oracle · PL/SQL</sub>

**Personal data inventory and masking tool**<br/>
Finds and classifies personal data across a database, masks it, generates synthetic data for test environments and produces a VERBİS-ready inventory.<br/>
<sub>.NET · Oracle · PostgreSQL</sub>

**GIDEON** — graduation project<br/>
A wake-word desktop assistant for Windows. Speech is transcribed locally with faster-whisper; trivial commands stay on a fast local router, and real coding and research tasks go to a GLM agent that runs behind a safety gate for destructive actions. Replies are spoken with edge-tts. The Python backend and the Electron UI talk over a local WebSocket: wake word → STT → intent router → agents → TTS.<br/>
<sub>Python · Electron · faster-whisper · openWakeWord · edge-tts · WebSockets</sub>

**RAG chatbot platform**<br/>
A retrieval-augmented assistant with a Turkish NLP pipeline: document chunking, vector search and answer generation.<br/>
<sub>Python · LangChain · vector search</sub>

→ [All repositories](https://github.com/hekimm?tab=repositories)

<br/>

## Stack

| | |
|---|---|
| Database | Oracle, PL/SQL, PostgreSQL, PostGIS, SQL Server — data modeling, query optimization |
| Cloud | Oracle Cloud Infrastructure, Docker |
| Backend | C#, .NET 8, ASP.NET Core, ASP.NET MVC, Dapper, Entity Framework, Node.js, SignalR, REST |
| Frontend | React, TypeScript, DevExpress, DevExtreme, Electron |
| AI | RAG, LangChain, faster-whisper, Python |
| Tools | Git, Linux |

## Certifications

| | |
|---|---|
| Oracle | OCI 2026 Certified Architect Associate · OCI 2026 Certified Foundations Associate · Oracle AI Database Certified Foundations Associate |
| HackerRank | Software Engineer (Role) · Frontend Developer, React (Role) · SQL (Advanced) · Problem Solving (Intermediate) · Rest API (Intermediate) |

<br/>

[hekimaktas.com](https://hekimaktas.com) · hekimcanaktas@gmail.com · Software Engineering, Manisa Celal Bayar University

<sub><i>quiet code, loud results.</i></sub>
