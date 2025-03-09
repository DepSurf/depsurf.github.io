# Function: <code>reuse_ksm_page</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543264,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2677",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543264,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608160,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608160,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823072,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2672",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823072,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493048576,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493048576,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226763348,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226763348,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286488240,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286488240,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272917830,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272917830,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576896,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576896,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518464,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518464,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568208,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568208,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "reuse_ksm_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633200,
      "name": "reuse_ksm_page",
      "external": true,
      "loc": "mm/ksm.c:2659",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633200,
      "name": "reuse_ksm_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```
</details>
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
bool reuse_ksm_page(struct page * page, struct vm_area_struct * vma, long unsigned int address)
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
