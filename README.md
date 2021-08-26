**Problem Statement**

Build 3 tier architecture resources using Terraform

**What do we mean by three-tier architecture**

It is an application architecture that organizes applications into three logical and physical computing tiers: 
-> Presentation tier(UI) 
-> Application tier (Processing)
-> Data tier (Storage)

**How we can easily build it in Azure?**

We will use 2 virtual machines and a SQL to do this, presentation tier will be managed by the Web server and Application by the App servers, Web server will have Inbound access from internet and app server will be connected to the SQL service

**How to use Terraform?**

We can use simple TF code to spin  up these VM machines, this can also be placed into modules and re used
