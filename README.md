# Free database hosting

A curated and up-to-date list of free database hosting services. Last updated June 2026.

> ⚠️ = notable limitation or caveat
> 👉 = recommended
> ~~strikethrough~~ = discontinued

| Service | Type | Storage | Limitations |
|---|---|---|---|
| Amazon DynamoDB | ⚠️ Proprietary NoSQL | 25 GB | ⚠️ Payment method required |
| Amazon RDS | ⚠️ Proprietary RDBMS | | ⚠️ Only free for 1 year |
| Azure SQL Database | MS SQL Server | | ⚠️ Only free for 1 year |
| 👉 Clever Cloud | PostgreSQL, MySQL, MongoDB, Redis | 256 MB (PostgreSQL) | Max 5 connections (PostgreSQL) |
| Cloudflare D1 | SQLite | 5 GB total / 500 MB per DB | Requires Cloudflare Workers account; 5M row reads/day, 100K row writes/day |
| ~~ElephantSQL~~ (discontinued) 😭 | PostgreSQL | 20 MB | Shut down January 27, 2025 |
| Fly.io | PostgreSQL | 3 GB | ⚠️ Credit card required, limited outbound traffic, no way to avoid accidental overage fees |
| Google Cloud Firestore | ⚠️ Proprietary NoSQL | 1 GB | ⚠️ After the first year there's no way to avoid accidental overage fees |
| ~~Heroku Postgres~~ (discontinued) 😭 | PostgreSQL | 10K max rows | |
| IBM Cloud Cloudant | ⚠️ Proprietary NoSQL | 1 GB | Deleted after 30 days of no activity |
| IBM Cloud Db2 | Db2 | 200 MB | ⚠️ Users are asked to re-extend their free account every 90 days by email. If you do not re-extend, your free account is cleaned out a further 90 days later |
| MongoDB Atlas | MongoDB | 512 MB | |
| 👉 Neon | PostgreSQL | 0.5 GB per project | 100 compute-hours/month, 5 GB egress/month, up to 100 projects |
| OpenShift Developer Sandbox | MariaDB, MongoDB, MySQL, PostgreSQL | 15 GB | ⚠️ Expires after 30 days (can resubscribe for free but not extend subscription), pods are automatically deleted after 12 consecutive hours of runtime |
| Oracle Cloud | Oracle Database | 20 GB each per two databases | ⚠️ Payment method required |
| Redis Enterprise | Redis | 30 MB | |
| Scalingo | PostgreSQL | 128 MB | Max 10 connections ⚠️ Payment method required after 30-day trial |
| 👉 Supabase | PostgreSQL | 500 MB | Paused after 1 week inactivity, 5 GB transfer limit, up to 2 free projects |
| Turso | SQLite (edge) | 9 GB total | 500 databases, 25B row reads/month, 50M row writes/month |

## Notes

- **ElephantSQL** shut down on January 27, 2025. Migrate to Neon or Supabase.
- **CockroachDB** retired its free serverless tier in late 2024; the self-hosted Core offering was also discontinued.
- **Heroku Postgres** free tier was removed in November 2022.
- **Neon** and **Turso** are strong modern picks for PostgreSQL and SQLite respectively.
- **Cloudflare D1** is a solid free SQLite option if you're already using Cloudflare Workers.

## Contributing

PRs welcome! Please keep entries accurate and note any limitations clearly.
