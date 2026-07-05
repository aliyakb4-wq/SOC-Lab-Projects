# Windows Security Event Analysis

## Event ID 4624 – Successful Logon

### Description
A user successfully logged into the Windows system.

### Why it matters
SOC analysts monitor this event to identify successful user logins.

---

## Event ID 4634 – Logoff

### Description
A user logged off from the Windows system.

### Why it matters
Helps analysts determine when a user session ended.

---

## Event ID 4648 – Logon Using Explicit Credentials

### Description
A logon attempt was made using explicit credentials.

### Why it matters
Useful for detecting credential usage and lateral movement.

---

## Event ID 4672 – Special Privileges Assigned

### Description
Special administrator privileges were assigned during logon.

### Why it matters
Indicates that an administrative account has logged in.
