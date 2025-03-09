# Function: <code>acpi_get_gpe_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583643561,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:920",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643561,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583966625,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:920",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966625,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584108378,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:963",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108378,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584175310,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:971",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175310,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584480184,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:971",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480184,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584702710,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:978",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702710,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584802810,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:978",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802810,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585005619,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:978",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585005619,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585141622,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1010",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141622,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585846715,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585846715,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585967866,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967866,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585844934,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585844934,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586331781,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586331781,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578348,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578348,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866640,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866640,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589156064,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589156064,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589462384,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1017",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462384,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_get_gpe_device",
      "external": false,
      "loc": "include/acpi/acpixf.h:754",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585043307,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1010",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043307,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584958867,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1010",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958867,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093206,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1010",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093206,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```

```json
{
  "name": "acpi_get_gpe_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199366,
      "name": "acpi_get_gpe_device",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:1010",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199366,
      "name": "acpi_get_gpe_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle * gpe_device)
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
