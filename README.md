I like the part of software where a wrong number or a lost write is a real bug. Most of my work is in Go: risk systems that can replay any past state, collaboration servers that never lose an edit, and network automation that catches drift before it breaks anything.

## Engineering Focus

<table>
<tr>
<td valign="top" width="50%">

<sub>BACKEND</sub>

### Backend & Data Systems

Go services and REST APIs on PostgreSQL and Redis: multi-tenant isolation with row-level security, append-only data models, background jobs and usage-based billing.

</td>
<td valign="top" width="50%">

<sub>REAL-TIME</sub>

### Real-time & Distributed Systems

WebSocket services and CRDT-based collaboration (Yjs) with durable persistence, horizontal scaling and conflict-free concurrent editing.

</td>
</tr>
<tr>
<td valign="top">

<sub>FINTECH</sub>

### FinTech & Risk Systems

Point-in-time market data, exact-decimal valuation, reconciliation, stress testing and ledgers where every number can be traced back to its source.

</td>
<td valign="top">

<sub>INFRASTRUCTURE</sub>

### Network Infrastructure & Automation

Reproducible network labs and intended-state automation: OSPF/BGP/IPsec topologies, NetBox-driven Ansible deploys, rollback and drift detection.

</td>
</tr>
</table>

## Selected Projects

<table>
<tr>
<td valign="top" width="50%">

<sub>FINTECH · RISK</sub>

### [atrisk](https://github.com/oplosy/atrisk)

Personal risk OS that joins macro data, portfolio exposure, stress tests and decisions on one point-in-time timeline, with backup/restore and a fail-closed release gate.

`Go` `Python` `React` `PostgreSQL`

</td>
<td valign="top" width="50%">

<sub>BACKEND · SAAS</sub>

### [fluxboard](https://github.com/oplosy/fluxboard)

Multi-tenant project management with usage-based billing, built as a Go modular monolith with Postgres row-level security and Stripe metered billing.

`Go` `PostgreSQL` `Redis` `Stripe`

</td>
</tr>
<tr>
<td valign="top">

<sub>REAL-TIME · DISTRIBUTED</sub>

### [crdt-server](https://github.com/oplosy/crdt-server)

Horizontally scalable Yjs collaboration server: WebSocket sync with CRDT persistence to Postgres, Redis and S3, plus auth, metrics and audit logging.

`Go` `WebSocket` `CRDT`

</td>
<td valign="top">

<sub>INFRASTRUCTURE · AUTOMATION</sub>

### [netaut](https://github.com/oplosy/netaut)

Intended-state network automation: NetBox YAML drives gated Ansible deploys with rollback and drift detection.

`Python` `Ansible` `NetBox` `Jinja2`

</td>
</tr>
</table>
