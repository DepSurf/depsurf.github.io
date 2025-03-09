# Function: <code>arch_gnttab_valloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578992146,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:90",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578988722,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:90",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990594,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:90",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578957026,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:90",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959632,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:117",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959632,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962144,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:117",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962144,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960240,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960240,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967248,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967248,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969680,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969680,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979312,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:93",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979312,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981488,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981488,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990608,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990608,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579007664,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007664,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025120,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025120,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053552,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053552,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053456,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053456,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078784,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:102",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078784,
      "name": "arch_gnttab_valloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969696,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969696,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969616,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969616,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_gnttab_valloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578970208,
      "name": "arch_gnttab_valloc",
      "external": false,
      "loc": "arch/x86/xen/grant-table.c:94",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970208,
      "name": "arch_gnttab_valloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area * area, unsigned int nr_frames)
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
