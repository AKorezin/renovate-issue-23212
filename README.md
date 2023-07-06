## Current state

```Dockerfile
FROM php:8.2.6-apache-bullseye
FROM node:18.16.0-alpine
FROM node:18.16.0
```

## Exected changes
```diff
--- a/Dockerfile
+++ b/Dockerfile
@@ -1,3 +1,3 @@
-FROM php:8.2.6-apache-bullseye
-FROM node:18.16.0-alpine
-FROM node:18.16.0
+FROM php:8.2.7-apache-bullseye
+FROM node:18.16.1-alpine
+FROM node:18.16.1
```

## Actual changes
!3
```diff
--- a/Dockerfile
+++ b/Dockerfile
@@ -1,3 +1,3 @@
 FROM php:8.2.6-apache-bullseye
 FROM node:18.16.0-alpine
-FROM node:18.16.0
+FROM node:18.16.1
```

## Issue dashboard
#2
