---
title: Using PostgreSQL with Entity Framework Core
date: "2018-12-30"
---

How to use PostGres instead of SQL Server.

<!-- end -->

## Steps

Add these dependencies to the WebApi and Model projects:
* Npsql (4.0.4)
* Npsql.EntityFrameworkCore.PostgreSQL (2.1.2)

Then amend the Startup.cs file so that PostgreSQL can be used as the database.

Then amend the initial migration script so that a new annotation is added for npsql.