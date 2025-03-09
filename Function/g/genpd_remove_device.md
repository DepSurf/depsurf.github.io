# Function: <code>genpd_remove_device</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585004932,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1230",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585090596,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1311",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585516308,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1434",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585761376,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1432",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585894576,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1511",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586132178,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1562",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586280789,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587046960,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1546",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587046960,
      "name": "genpd_remove_device",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130736,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1611",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130736,
      "name": "genpd_remove_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018112,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1607",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018112,
      "name": "genpd_remove_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583392,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1647",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583392,
      "name": "genpd_remove_device",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588919312,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1682",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588919312,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590431216,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1661",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590431216,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590750704,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1687",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590750704,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589995696,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/pmdomain/core.c:1694",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589995696,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499108488,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499108488,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231651752,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231651752,
      "name": "genpd_remove_device",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292293168,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292293168,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276429458,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:__genpd_dev_pm_attach",
        "drivers/base/power/domain.c:genpd_dev_pm_detach",
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276429458,
      "name": "genpd_remove_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586044037,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585890037,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586230805,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_remove_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586335941,
      "name": "genpd_remove_device",
      "external": false,
      "loc": "drivers/base/power/domain.c:1557",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int genpd_remove_device(struct generic_pm_domain * genpd, struct device * dev)
```
</details>
</li>
</ul>
