# Commands Used

The following Windows commands were executed during the Sysmon Log Analysis lab to generate events for monitoring and analysis.

## Command 1

```powershell
tasklist
```

**Purpose:** Lists all running processes.

---

## Command 2

```powershell
whoami
```

**Purpose:** Displays the currently logged-in user.

---

## Command 3

```powershell
ipconfig /all
```

**Purpose:** Displays detailed network configuration.

---

## Command 4

```powershell
net user
```

**Purpose:** Displays local user accounts.

---

## Command 5

```powershell
powershell
```

**Purpose:** Launches Windows PowerShell and generates a Process Creation event.

---

## Outcome

These commands generated Sysmon Event ID 1 (Process Creation), which was analyzed using Windows Event Viewer.
