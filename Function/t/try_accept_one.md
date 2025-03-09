# Function: <code>try_accept_one</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool try_accept_one(phys_addr_t * start, long unsigned int len, enum pg_level pg_level)
```

```json
{
  "name": "try_accept_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578859368,
      "name": "try_accept_one",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:662",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed"
      ],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856336,
      "name": "try_accept_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool try_accept_one(phys_addr_t * start, long unsigned int len, enum pg_level pg_level)
```

```json
{
  "name": "try_accept_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861432,
      "name": "try_accept_one",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:704",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed"
      ],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858960,
      "name": "try_accept_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_accept_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860395,
      "name": "try_accept_one",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx-shared.c:4",
      "file": "arch/x86/coco/tdx/tdx-shared.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory",
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory",
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int try_accept_one(phys_addr_t start, long unsigned int len, enum pg_level pg_level)
```

```json
{
  "name": "try_accept_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578861040,
      "name": "try_accept_one",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx-shared.c:4",
      "file": "arch/x86/coco/tdx/tdx-shared.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory",
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory",
        "arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578861040,
      "name": "try_accept_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
bool try_accept_one(phys_addr_t * start, long unsigned int len, enum pg_level pg_level)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool try_accept_one(phys_addr_t * start, long unsigned int len, enum pg_level pg_level)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long unsigned int try_accept_one(phys_addr_t start, long unsigned int len, enum pg_level pg_level)
```
</details>
</li>
</ul>
