# Function: <code>acpi_dev_resource_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583571880,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:87",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_tis.c:tpm_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571880,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894177,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:100",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_tis.c:tpm_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894177,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033539,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:113",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_tis.c:tpm_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033539,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584087648,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:113",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087648,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358416,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:113",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358416,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584579424,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:113",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584579424,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676816,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:113",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676816,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877072,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877072,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012944,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012944,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585714192,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585714192,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836304,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836304,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585715616,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715616,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586196944,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586196944,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587433712,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/resource.c:acpi_dev_process_resource",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587433712,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588691616,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/resource.c:acpi_dev_process_resource",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691616,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979520,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/resource.c:acpi_dev_process_resource",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979520,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283280,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:106",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/resource.c:acpi_dev_process_resource",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283280,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497423736,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497423736,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956304,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956304,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865104,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865104,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964528,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964528,
      "name": "acpi_dev_resource_memory",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```

```json
{
  "name": "acpi_dev_resource_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585070704,
      "name": "acpi_dev_resource_memory",
      "external": true,
      "loc": "drivers/acpi/resource.c:105",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_get_resource_memory",
        "drivers/acpi/resource.c:is_memory",
        "drivers/acpi/acpi_lpss.c:is_memory",
        "drivers/acpi/acpi_apd.c:misc_check_res",
        "drivers/acpi/ioapic.c:setup_res",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/char/tpm/tpm_crb.c:crb_check_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070704,
      "name": "acpi_dev_resource_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource * ares, struct resource * res)
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
