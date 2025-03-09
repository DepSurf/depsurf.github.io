# Function: <code>acpi_get_phys_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573885,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:182",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573885,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583896354,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:200",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896354,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036259,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:220",
      "file": "drivers/acpi/processor_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036259,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584092816,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:198",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092816,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584364224,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:198",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584364224,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584585248,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:198",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585248,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584682656,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:198",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584682656,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584882944,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584882944,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585018848,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018848,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585720853,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720592,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585842931,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:196",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585842656,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585721184,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:196",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721184,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586202992,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:196",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202992,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587440224,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:196",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440224,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588699904,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:196",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699904,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588988048,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:225",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588988048,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589292577,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:254",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589292176,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497429112,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497429112,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961312,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961312,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584870112,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870112,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970432,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970432,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```

```json
{
  "name": "acpi_get_phys_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585076608,
      "name": "acpi_get_phys_id",
      "external": true,
      "loc": "drivers/acpi/processor_core.c:199",
      "file": "drivers/acpi/processor_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_cpuid",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076608,
      "name": "acpi_get_phys_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id)
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
