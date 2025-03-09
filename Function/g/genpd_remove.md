# Function: <code>genpd_remove</code>

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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584999372,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1492",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585084236,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1578",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585508140,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1702",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585752951,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1703",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585886471,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1784",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586123729,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1851",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586272369,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038832,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1836",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038832,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587125920,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1998",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587125920,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587012272,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1994",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012272,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:2034",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578880,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
    },
    {
      "addr": 18446744071592492928,
      "name": "genpd_remove.cold",
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:2111",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913232,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071594362991,
      "name": "genpd_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:2093",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590425312,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071596247533,
      "name": "genpd_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:2119",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590744864,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071596775844,
      "name": "genpd_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/pmdomain/core.c:2127",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589989600,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071597662389,
      "name": "genpd_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499094336,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499094336,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231646836,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231646836,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292277840,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292277840,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int genpd_remove(struct generic_pm_domain * genpd)
```

```json
{
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276421434,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:pm_genpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276421434,
      "name": "genpd_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586035617,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585881633,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586222385,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
  "name": "genpd_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586331809,
      "name": "genpd_remove",
      "external": false,
      "loc": "drivers/base/power/domain.c:1846",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_remove"
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
int genpd_remove(struct generic_pm_domain * genpd)
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
int genpd_remove(struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int genpd_remove(struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int genpd_remove(struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int genpd_remove(struct generic_pm_domain * genpd)
```
</details>
</li>
</ul>
