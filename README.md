# -From 3ef91567abf09ca07380012ecc1a1ab705d94a4c Mon Sep 17 00:00:00 2001
From: 0x0 <xsw.mail.0@gmail.com>
Date: Fri, 7 May 2021 19:23:50 +0800
Subject: [PATCH] update .github/workflows/AutoDailyCP.yml.

---
 .github/workflows/AutoDailyCP.yml | 1 +
 1 file changed, 1 insertion(+)

diff --git a/.github/workflows/AutoDailyCP.yml b/.github/workflows/AutoDailyCP.yml
index d221aa9..62db259 100644
--- a/.github/workflows/AutoDailyCP.yml
+++ b/.github/workflows/AutoDailyCP.yml
@@ -18,6 +18,7 @@ on:
 jobs:
   build:
     runs-on: ubuntu-latest
+    timeout-minutes: 30
     if: github.event.repository.owner.id == github.event.sender.id
     steps:
       - name: Checkout
-- 
Gitee
