# Function: <code>find_timens_vvar_page</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868385,
      "name": "find_timens_vvar_page",
      "external": false,
      "loc": "arch/x86/entry/vdso/vma.c:117",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864209,
      "name": "find_timens_vvar_page",
      "external": false,
      "loc": "arch/x86/entry/vdso/vma.c:101",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864193,
      "name": "find_timens_vvar_page",
      "external": false,
      "loc": "arch/x86/entry/vdso/vma.c:101",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
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
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578865777,
      "name": "find_timens_vvar_page",
      "external": false,
      "loc": "arch/x86/entry/vdso/vma.c:101",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
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
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861684,
      "name": "find_timens_vvar_page",
      "external": false,
      "loc": "arch/x86/entry/vdso/vma.c:101",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct page * find_timens_vvar_page(struct vm_area_struct * vma)
```

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886640,
      "name": "find_timens_vvar_page",
      "external": true,
      "loc": "kernel/time/namespace.c:195",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886640,
      "name": "find_timens_vvar_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct page * find_timens_vvar_page(struct vm_area_struct * vma)
```

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970480,
      "name": "find_timens_vvar_page",
      "external": true,
      "loc": "kernel/time/namespace.c:195",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970480,
      "name": "find_timens_vvar_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct page * find_timens_vvar_page(struct vm_area_struct * vma)
```

```json
{
  "name": "find_timens_vvar_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065216,
      "name": "find_timens_vvar_page",
      "external": true,
      "loc": "kernel/time/namespace.c:195",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065216,
      "name": "find_timens_vvar_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct page * find_timens_vvar_page(struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
