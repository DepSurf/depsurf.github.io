# Function: <code>acpi_os_read_iomem</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584312272,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:666",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312064,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532445,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:671",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532240,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584629773,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:674",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629568,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584829458,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:660",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829248,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584965186,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964976,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585660738,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660528,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786369,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:684",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786144,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585666739,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:685",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666512,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586146211,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:685",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145984,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378692,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:687",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378416,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588628564,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:687",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588628272,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588916324,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:687",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588916032,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589212388,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:684",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212096,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497379976,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497379976,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
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
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584915362,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915152,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584821282,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821072,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584916770,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916560,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```

```json
{
  "name": "acpi_os_read_iomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585022870,
      "name": "acpi_os_read_iomem",
      "external": true,
      "loc": "drivers/acpi/osl.c:680",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_read_memory"
      ],
      "caller_func": [
        "drivers/acpi/acpi_lpit.c:lpit_read_residency_counter_us"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585022640,
      "name": "acpi_os_read_iomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_os_read_iomem(void * virt_addr, u64 * value, u32 width)
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
