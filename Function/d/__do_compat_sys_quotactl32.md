# Function: <code>__do_compat_sys_quotactl32</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582082954,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582177082,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582340218,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582439354,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_quotactl32(unsigned int cmd, const char * special, qid_t id, void * addr)
```

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732960,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732960,
      "name": "__do_compat_sys_quotactl32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408090,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582345786,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582398570,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_quotactl32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582478106,
      "name": "__do_compat_sys_quotactl32",
      "external": false,
      "loc": "fs/quota/compat.c:44",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_quotactl32(unsigned int cmd, const char * special, qid_t id, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_quotactl32(unsigned int cmd, const char * special, qid_t id, void * addr)
```
</details>
</li>
</ul>
