# Function: <code>audit_log_link_denied</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation, struct path * link)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039648,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:1924",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:may_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039648,
      "name": "audit_log_link_denied",
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
void audit_log_link_denied(const char * operation, struct path * link)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072352,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:1945",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072352,
      "name": "audit_log_link_denied",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation, const struct path * link)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112576,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2084",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112576,
      "name": "audit_log_link_denied",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation, const struct path * link)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118128,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2251",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118128,
      "name": "audit_log_link_denied",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation, const struct path * link)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170608,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2259",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:may_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170608,
      "name": "audit_log_link_denied",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230592,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2311",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230592,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282992,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2308",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282992,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580333040,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2161",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333040,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381904,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381904,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491647624,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491647624,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225599636,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225599636,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284644864,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284644864,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272042418,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272042418,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580350704,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350704,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297872,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297872,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341952,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341952,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void audit_log_link_denied(const char * operation)
```

```json
{
  "name": "audit_log_link_denied",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580397232,
      "name": "audit_log_link_denied",
      "external": true,
      "loc": "kernel/audit.c:2163",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_linkat",
        "fs/namei.c:trailing_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397232,
      "name": "audit_log_link_denied",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * link</code> ➡️ <code>const struct path * link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct path * link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void audit_log_link_denied(const char * operation)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
