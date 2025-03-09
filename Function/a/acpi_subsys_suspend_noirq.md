# Function: <code>acpi_subsys_suspend_noirq</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332656,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1049",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332656,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584555072,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1049",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555072,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584652832,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1050",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652832,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584852128,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1094",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584852128,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584987968,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584987968,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684336,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684336,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585806720,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1095",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806720,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585687408,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1094",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687408,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586167568,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1094",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167568,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587400992,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1120",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400992,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654672,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1182",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654672,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588942624,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1182",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942624,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589239248,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1195",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239248,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497396776,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497396776,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584932368,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932368,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584841168,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841168,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584939552,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939552,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
```

```json
{
  "name": "acpi_subsys_suspend_noirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585045728,
      "name": "acpi_subsys_suspend_noirq",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1099",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045728,
      "name": "acpi_subsys_suspend_noirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int acpi_subsys_suspend_noirq(struct device * dev)
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
int acpi_subsys_suspend_noirq(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_subsys_suspend_noirq(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_subsys_suspend_noirq(struct device * dev)
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
