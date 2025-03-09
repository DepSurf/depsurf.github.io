# Function: <code>__kernel_physical_mapping_init</code>

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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589939789,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589939789,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167341,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167341,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591185966,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:730",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185966,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591681319,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:725",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591681319,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591624810,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:725",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591624810,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592798137,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:726",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592798137,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594698156,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:725",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594698156,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596437200,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:726",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596437200,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 987
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596977984,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:726",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596977984,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597906416,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:726",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597906416,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589769629,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589769629,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589492576,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589492576,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590213037,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590213037,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```

```json
{
  "name": "__kernel_physical_mapping_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590263405,
      "name": "__kernel_physical_mapping_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:722",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_change",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590263405,
      "name": "__kernel_physical_mapping_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param reordered. </b>
<code>paddr_start, paddr_end, page_size_mask, init</code> ➡️ <code>paddr_start, paddr_end, page_size_mask, prot, init</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int __kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, bool init)
```
</details>
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
