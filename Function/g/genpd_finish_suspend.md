# Function: <code>genpd_finish_suspend</code>

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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085664,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:913",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_poweroff_noirq",
        "drivers/base/power/domain.c:pm_genpd_poweroff_noirq",
        "drivers/base/power/domain.c:pm_genpd_suspend_noirq",
        "drivers/base/power/domain.c:pm_genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085664,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511136,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1032",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511136,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585756048,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1033",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585756048,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585890416,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1112",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890416,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586127280,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1115",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586127280,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276656,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276656,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043408,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1099",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043408,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587127312,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1144",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127312,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587013664,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1139",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013664,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587584896,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1179",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584896,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588916048,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1197",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588916048,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int genpd_finish_suspend(struct device * dev, int (*)(struct device *) suspend_noirq, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590437232,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1219",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_freeze_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590437232,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int genpd_finish_suspend(struct device * dev, int (*)(struct device *) suspend_noirq, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590756896,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1245",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_freeze_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590756896,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int genpd_finish_suspend(struct device * dev, int (*)(struct device *) suspend_noirq, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590001952,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/pmdomain/core.c:1252",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:genpd_poweroff_noirq",
        "drivers/pmdomain/core.c:genpd_freeze_noirq",
        "drivers/pmdomain/core.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590001952,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499105928,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499105928,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231656804,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231656804,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292288944,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292288944,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039904,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039904,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885920,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885920,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226672,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226672,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
```

```json
{
  "name": "genpd_finish_suspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586336496,
      "name": "genpd_finish_suspend",
      "external": false,
      "loc": "drivers/base/power/domain.c:1110",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_poweroff_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq",
        "drivers/base/power/domain.c:genpd_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336496,
      "name": "genpd_finish_suspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*)(struct device *) suspend_noirq</code>
</li>
<li>
<b>Param added. </b>
<code>int (*)(struct device *) resume_noirq</code>
</li>
<li>
<b>Param removed. </b>
<code>bool poweroff</code>
</li>
</ul>
</details>
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
int genpd_finish_suspend(struct device * dev, bool poweroff)
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
