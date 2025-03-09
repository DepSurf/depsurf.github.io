# Function: <code>efi_mem_reserve</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595761219,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:420",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595761219,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596690245,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:419",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596690245,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603020276,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:439",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603020276,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603192942,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:450",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603192942,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605003131,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:460",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605003131,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605115355,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:460",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605115355,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605154772,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605154772,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609424507,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:493",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609424507,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612498336,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:497",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612498336,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614640248,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:497",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614640248,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615598073,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:497",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615598073,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617407155,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:508",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617407155,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628159088,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:516",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628159088,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619926304,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:551",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619926304,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622237440,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:573",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622237440,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511281940,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511281940,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243933108,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243933108,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605045210,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605045210,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605010550,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605010550,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605131785,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605131785,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void efi_mem_reserve(phys_addr_t addr, u64 size)
```

```json
{
  "name": "efi_mem_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605158966,
      "name": "efi_mem_reserve",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:448",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605158966,
      "name": "efi_mem_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size)
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
