# Function: <code>kernel_quotactl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079584,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:838",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079584,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2193
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173680,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:837",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173680,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2235
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338432,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338432,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437616,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437616,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732000,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:819",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732000,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
    }
  ]
}
```
</details>
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494051312,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__arm64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494051312,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227511952,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__se_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227511952,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287706352,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__se_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287706352,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273552202,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__se_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273552202,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406352,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406352,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344048,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344048,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582396832,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396832,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "kernel_quotactl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476368,
      "name": "kernel_quotactl",
      "external": true,
      "loc": "fs/quota/quota.c:823",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476368,
      "name": "kernel_quotactl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int kernel_quotactl(unsigned int cmd, const char * special, qid_t id, void * addr)
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
