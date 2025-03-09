# Function: <code>audit_reset_context</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_reset_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_reset_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_reset_context",
      "external": false,
      "loc": "kernel/auditsc.c:970",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840592,
      "name": "audit_reset_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
    },
    {
      "addr": 18446744071593935763,
      "name": "audit_reset_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_reset_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_reset_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_reset_context",
      "external": false,
      "loc": "kernel/auditsc.c:973",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127680,
      "name": "audit_reset_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071596000700,
      "name": "audit_reset_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_reset_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_reset_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_reset_context",
      "external": false,
      "loc": "kernel/auditsc.c:974",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217168,
      "name": "audit_reset_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071596519193,
      "name": "audit_reset_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void audit_reset_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_reset_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_reset_context",
      "external": false,
      "loc": "kernel/auditsc.c:972",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_uring_exit",
        "kernel/auditsc.c:__audit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323584,
      "name": "audit_reset_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071597419631,
      "name": "audit_reset_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void audit_reset_context(struct audit_context * ctx)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
