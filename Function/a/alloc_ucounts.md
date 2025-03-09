# Function: <code>alloc_ucounts</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724128,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:146",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:set_cred_ucounts",
        "kernel/cred.c:set_cred_ucounts",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724128,
      "name": "alloc_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803520,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:162",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803520,
      "name": "alloc_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913232,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:168",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913232,
      "name": "alloc_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067104,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:164",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067104,
      "name": "alloc_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120432,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:164",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120432,
      "name": "alloc_ucounts",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "alloc_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165968,
      "name": "alloc_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:165",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:copy_creds",
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165968,
      "name": "alloc_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct ucounts * alloc_ucounts(struct user_namespace * ns, kuid_t uid)
```
</details>
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
