# Function: <code>__xen_write_cr3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978512,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1421",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978512,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978512,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1422",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978512,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980416,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1422",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980416,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979904,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1411",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979904,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982880,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1369",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982880,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578984944,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1396",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578984944,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578984032,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1404",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578984032,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998288,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071579008145,
      "name": "__xen_write_cr3.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999792,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999792,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579008848,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008848,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579007984,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1296",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007984,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018320,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1295",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018320,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579036256,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1295",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036256,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057216,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057216,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088560,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1309",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088560,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088784,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1318",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088784,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114576,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1318",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114576,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579000144,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000144,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999728,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999728,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```

```json
{
  "name": "__xen_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579002544,
      "name": "__xen_write_cr3",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1394",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002544,
      "name": "__xen_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
