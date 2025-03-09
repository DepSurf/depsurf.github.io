# Function: <code>memtype_check_conflict</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode * newtype)
```

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438096,
      "name": "memtype_check_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071579439822,
      "name": "memtype_check_conflict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode * newtype)
```

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436496,
      "name": "memtype_check_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591271416,
      "name": "memtype_check_conflict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579440503,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579504887,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579586999,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579697176,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579711031,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memtype_check_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579745735,
      "name": "memtype_check_conflict",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:78",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert"
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
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode * newtype)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode * newtype)
```
</details>
</li>
</ul>
