# Function: <code>audit_log_object_context</code>

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
int audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580448720,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2183",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580448720,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437312,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2200",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:show_special",
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437312,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441040,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2200",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441040,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605872,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2239",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605872,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814544,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2290",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814544,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100784,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2288",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100784,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192400,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2288",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192400,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_object_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_object_context",
      "external": true,
      "loc": "kernel/audit.c:2308",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_log_pid_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597419584,
      "name": "audit_log_object_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581298688,
      "name": "audit_log_object_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int audit_log_object_context(struct audit_buffer * ab, struct lsmblob * blob)
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
