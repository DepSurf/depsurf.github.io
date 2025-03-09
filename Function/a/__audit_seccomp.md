# Function: <code>__audit_seccomp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```

```json
{
  "name": "__audit_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063936,
      "name": "__audit_seccomp",
      "external": true,
      "loc": "kernel/auditsc.c:2406",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_phase2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063936,
      "name": "__audit_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```

```json
{
  "name": "__audit_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097136,
      "name": "__audit_seccomp",
      "external": true,
      "loc": "kernel/auditsc.c:2410",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097136,
      "name": "__audit_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```

```json
{
  "name": "__audit_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137456,
      "name": "__audit_seccomp",
      "external": true,
      "loc": "kernel/auditsc.c:2418",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137456,
      "name": "__audit_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```

```json
{
  "name": "__audit_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143296,
      "name": "__audit_seccomp",
      "external": true,
      "loc": "kernel/auditsc.c:2440",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143296,
      "name": "__audit_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```

```json
{
  "name": "__audit_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195968,
      "name": "__audit_seccomp",
      "external": true,
      "loc": "kernel/auditsc.c:2469",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195968,
      "name": "__audit_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void __audit_seccomp(long unsigned int syscall, long int signr, int code)
```
</details>
</li>
</ul>
