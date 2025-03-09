# Function: <code>security_lsm_slot_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * security_lsm_slot_name(int slot)
```

```json
{
  "name": "security_lsm_slot_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731840,
      "name": "security_lsm_slot_name",
      "external": true,
      "loc": "security/security.c:497",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731840,
      "name": "security_lsm_slot_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const char * security_lsm_slot_name(int slot)
```

```json
{
  "name": "security_lsm_slot_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852160,
      "name": "security_lsm_slot_name",
      "external": true,
      "loc": "security/security.c:499",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852160,
      "name": "security_lsm_slot_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const char * security_lsm_slot_name(int slot)
```

```json
{
  "name": "security_lsm_slot_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876992,
      "name": "security_lsm_slot_name",
      "external": true,
      "loc": "security/security.c:502",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876992,
      "name": "security_lsm_slot_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
const char * security_lsm_slot_name(int slot)
```

```json
{
  "name": "security_lsm_slot_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241856,
      "name": "security_lsm_slot_name",
      "external": true,
      "loc": "security/security.c:502",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_log_object_context",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_log_lsm",
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241856,
      "name": "security_lsm_slot_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * security_lsm_slot_name(int slot)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
const char * security_lsm_slot_name(int slot)
```
</details>
</li>
</ul>
