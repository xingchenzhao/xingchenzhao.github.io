---
layout: project
type: project
image: images/pittsocial.png
title: Pitt Social
permalink: projects/pittsocial
# All dates must be YYYY-MM-DD format!
date: 2019-12-12
labels:
  - Java
  - JDBC
  - Database
  - SQL
  - PostgreSQL
summary: A Java and Database application program that will operate PittSocial, a Social Networking System for the University of Pittsburgh.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/pittsocial.png">
</div>

# PittSocial (https://github.com/xingchenzhao/PittSocial)

> An application program that will operate PittSocial, implemented by Java, PostgreSQL, and JDBC.

## Course Team Project

The primary goal of this project is to implement a single Java application program that will operate PittSocial, a Social Networking System for the University of Pittsburgh. The core of such a system is a database system. The secondary goal is to learn how to work as a member of a team which designs and develops a relatively large, real database application.

## Quick Start

```
Run PittSocial.java as an application.

javac -cp postgresql-42.2.5.jar pittsocial.java
java -cp postgresql-42.2.5.jar:. pittsocial

javac -cp postgresql-42.2.5.jar driver.java
java -cp postgresql-42.2.5.jar:. driver
```

```java
//Remeber to modify database credentials at the start of the class) Run Driver.java for general testing. (Remeber to modify //database credentials at the start of the PittSocial class and Driver class)

//open pittsocial.java and find the following codes
static String DB_username = "postgres"; // modify here
static String DB_password = "xxx"; // modify here
static String url = "jdbc:postgresql://localhost:5432/pitt_social?currentSchema=public";//modify here
```
