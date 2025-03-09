# Function: <code>pm_generic_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584434394,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:294",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434528,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584770266,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:294",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770400,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584960666,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:294",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:pm_genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960800,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585045338,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:294",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:pm_genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045472,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468288,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:293",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468288,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712144,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:293",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712144,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843776,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:293",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843776,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586079984,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079984,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228416,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228416,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586994336,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994336,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587079088,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587079088,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965360,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965360,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531504,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531504,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862320,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862320,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369312,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369312,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590689808,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590689808,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591051264,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/pmdomain/core.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591051264,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499040504,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499040504,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231599044,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231599044,
      "name": "pm_generic_complete",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292211776,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292211776,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585988624,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/acpi/device_pm.c:acpi_subsys_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988624,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585837888,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837888,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586178432,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178432,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pm_generic_complete(struct device * dev)
```

```json
{
  "name": "pm_generic_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287056,
      "name": "pm_generic_complete",
      "external": true,
      "loc": "drivers/base/power/generic_ops.c:291",
      "file": "drivers/base/power/generic_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_complete",
        "drivers/base/power/domain.c:genpd_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287056,
      "name": "pm_generic_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pm_generic_complete(struct device * dev)
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
