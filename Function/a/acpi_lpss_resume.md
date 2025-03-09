# Function: <code>acpi_lpss_resume</code>

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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584391680,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:825",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391680,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613392,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:982",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613392,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584711456,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711456,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912560,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1012",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912560,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585048272,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1037",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585048272,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585752432,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1015",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752432,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871552,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1027",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871552,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749312,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1028",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749312,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1029",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231920,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071592412842,
      "name": "acpi_lpss_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1051",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470304,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071594280229,
      "name": "acpi_lpss_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1040",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737536,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071596219389,
      "name": "acpi_lpss_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1055",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025664,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071596745925,
      "name": "acpi_lpss_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1019",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589329792,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071597654573,
      "name": "acpi_lpss_resume.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584895296,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1037",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584895296,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999856,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1037",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999856,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int acpi_lpss_resume(struct device * dev)
```

```json
{
  "name": "acpi_lpss_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585106032,
      "name": "acpi_lpss_resume",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:1037",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585106032,
      "name": "acpi_lpss_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int acpi_lpss_resume(struct device * dev)
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
int acpi_lpss_resume(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_lpss_resume(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_lpss_resume(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_lpss_resume(struct device * dev)
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
int acpi_lpss_resume(struct device * dev)
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
