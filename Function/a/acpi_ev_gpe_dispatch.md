# Function: <code>acpi_ev_gpe_dispatch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630092,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:699",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630092,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953149,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:699",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953149,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094816,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:754",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094816,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584161592,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:754",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584161592,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456341,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:754",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456341,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680341,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:742",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680341,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780317,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:742",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780317,
      "name": "acpi_ev_gpe_dispatch",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982958,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982958,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118958,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118958,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823761,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823761,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585944583,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944583,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821833,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821833,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586308304,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308304,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587553703,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553703,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588837024,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837024,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126368,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126368,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432240,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432240,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585028894,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028894,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584944512,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944512,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585070542,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070542,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```

```json
{
  "name": "acpi_ev_gpe_dispatch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176702,
      "name": "acpi_ev_gpe_dispatch",
      "external": true,
      "loc": "drivers/acpi/acpica/evgpe.c:748",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176702,
      "name": "acpi_ev_gpe_dispatch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node * gpe_device, struct acpi_gpe_event_info * gpe_event_info, u32 gpe_number)
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
