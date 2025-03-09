# Function: <code>__fuse_dax_fault</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679616,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:791",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679616,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704240,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:791",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704240,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064848,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:790",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064848,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655936,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:787",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655936,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585337760,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:787",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337760,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567696,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:787",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567696,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, unsigned int order, bool write)
```

```json
{
  "name": "__fuse_dax_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585806032,
      "name": "__fuse_dax_fault",
      "external": false,
      "loc": "fs/fuse/dax.c:787",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dax.c:fuse_dax_huge_fault",
        "fs/fuse/dax.c:fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806032,
      "name": "__fuse_dax_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
vm_fault_t __fuse_dax_fault(struct vm_fault * vmf, enum page_entry_size pe_size, bool write)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_entry_size pe_size</code>
</li>
</ul>
</details>
</li>
</ul>
