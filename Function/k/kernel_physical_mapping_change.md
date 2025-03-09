# Function: <code>kernel_physical_mapping_change</code>

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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589940480,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589940480,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590168032,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168032,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591186525,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:802",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186525,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591681838,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:797",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591681838,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591625335,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:797",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625335,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592798722,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:798",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592798722,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594698784,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:797",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594698784,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596438256,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:798",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596438256,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596979072,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:798",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596979072,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597907504,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:798",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597907504,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770320,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770320,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589493149,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589493149,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590213728,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590213728,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```

```json
{
  "name": "kernel_physical_mapping_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590264096,
      "name": "kernel_physical_mapping_change",
      "external": true,
      "loc": "arch/x86/mm/init_64.c:794",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590264096,
      "name": "kernel_physical_mapping_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
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
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask)
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
