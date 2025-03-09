# Function: <code>acpi_lpss_suspend</code>

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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584392384,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:804",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392384,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584614368,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:960",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614368,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584714064,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:993",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714064,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584913696,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:990",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913696,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585049408,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049408,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585750304,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:993",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750304,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869488,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1005",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869488,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585747024,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1006",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747024,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586229568,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1007",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229568,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587468048,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1029",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468048,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588735024,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1018",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735024,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589023152,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1033",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589023152,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327408,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:997",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327408,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584896352,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896352,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585000992,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000992,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```

```json
{
  "name": "acpi_lpss_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585107168,
      "name": "acpi_lpss_suspend",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585107168,
      "name": "acpi_lpss_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int acpi_lpss_suspend(struct device * dev, bool wakeup)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int acpi_lpss_suspend(struct device * dev, bool wakeup)
```
</details>
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
