# Function: <code>acpi_pm_set_device_wakeup</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064688,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:733",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064688,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332448,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:816",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332448,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553200,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:816",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553200,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584650944,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:817",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650944,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584850432,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:861",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850432,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986176,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986176,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585684912,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684912,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585806928,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:851",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806928,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585689440,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:848",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689440,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169840,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:848",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169840,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587401968,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:874",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587401968,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588656144,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:936",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588656144,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944096,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:936",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944096,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240720,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:949",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240720,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497398000,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497398000,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930832,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930832,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839568,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839568,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584937760,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937760,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "acpi_pm_set_device_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043936,
      "name": "acpi_pm_set_device_wakeup",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:866",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043936,
      "name": "acpi_pm_set_device_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```
</details>
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
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_pm_set_device_wakeup(struct device * dev, bool enable)
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
