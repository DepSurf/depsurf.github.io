# Function: <code>cr4_set_bits_and_update_boot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578963350,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:80",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595062828,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:80",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959798,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:128",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595228532,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:128",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961862,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:128",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595471574,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:128",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596392797,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:143",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602711354,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:312",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602883899,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:357",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604680909,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:345",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604780396,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:347",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604806163,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:363",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387179,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:200",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387179,
      "name": "cr4_set_bits_and_update_boot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591266212,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:201",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266212,
      "name": "cr4_set_bits_and_update_boot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591208523,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:210",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208523,
      "name": "cr4_set_bits_and_update_boot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592082122,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:208",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082122,
      "name": "cr4_set_bits_and_update_boot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593849651,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:217",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849651,
      "name": "cr4_set_bits_and_update_boot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627711981,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:218",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619469325,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:219",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621765837,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/mm/init.c:218",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720105,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:363",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604688048,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:363",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604797672,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:363",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
  "name": "cr4_set_bits_and_update_boot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604810291,
      "name": "cr4_set_bits_and_update_boot",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:363",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
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
void cr4_set_bits_and_update_boot(long unsigned int mask)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask)
```
</details>
</li>
</ul>
