# Function: <code>audit_log_path_denied</code>

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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459040,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2313",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459040,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580447536,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2330",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447536,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451424,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2330",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451424,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580616576,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2369",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616576,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821824,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2415",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821824,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108240,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2413",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108240,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199888,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2413",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199888,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void audit_log_path_denied(int type, const char * operation)
```

```json
{
  "name": "audit_log_path_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306000,
      "name": "audit_log_path_denied",
      "external": true,
      "loc": "kernel/audit.c:2435",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306000,
      "name": "audit_log_path_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void audit_log_path_denied(int type, const char * operation)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
