# Function: <code>genpd_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool timed)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805120,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:135",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805120,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int genpd_power_off(struct generic_pm_domain * genpd, bool timed)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997488,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:234",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997488,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585088032,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:295",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585088032,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585513632,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:422",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513632,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585758704,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:423",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758704,
      "name": "genpd_power_off",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891840,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:498",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891840,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586129576,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:499",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586129472,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071586133347,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586278264,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278160,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071586281832,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587049714,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048288,
      "name": "genpd_power_off.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071587050805,
      "name": "genpd_power_off.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587134498,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:547",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133040,
      "name": "genpd_power_off.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071591489619,
      "name": "genpd_power_off.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587020050,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:579",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018592,
      "name": "genpd_power_off.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071591432637,
      "name": "genpd_power_off.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587586961,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:613",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585344,
      "name": "genpd_power_off.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071592493092,
      "name": "genpd_power_off.part.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:621",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922096,
      "name": "genpd_power_off.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071594363125,
      "name": "genpd_power_off.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:643",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434000,
      "name": "genpd_power_off.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    },
    {
      "addr": 18446744071596247554,
      "name": "genpd_power_off.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:669",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590753664,
      "name": "genpd_power_off.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    },
    {
      "addr": 18446744071596775865,
      "name": "genpd_power_off.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/pmdomain/core.c:676",
      "file": "drivers/pmdomain/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:genpd_runtime_resume",
        "drivers/pmdomain/core.c:genpd_runtime_suspend",
        "drivers/pmdomain/core.c:genpd_power_off_work_fn",
        "drivers/pmdomain/core.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589998720,
      "name": "genpd_power_off.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    },
    {
      "addr": 18446744071597662410,
      "name": "genpd_power_off.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499103952,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499103952,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231657284,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231657284,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292294800,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292290160,
      "name": "genpd_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276427832,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276427832,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586041512,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041408,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071586045080,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585887784,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887680,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071585891068,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586228280,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228176,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071586231848,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```

```json
{
  "name": "genpd_power_off",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586338744,
      "name": "genpd_power_off",
      "external": false,
      "loc": "drivers/base/power/domain.c:494",
      "file": "drivers/base/power/domain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_runtime_resume",
        "drivers/base/power/domain.c:genpd_runtime_suspend",
        "drivers/base/power/domain.c:genpd_power_off_work_fn",
        "drivers/base/power/domain.c:genpd_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586338640,
      "name": "genpd_power_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071586340885,
      "name": "genpd_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool timed)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool one_dev_on</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int depth</code>
</li>
<li>
<b>Param removed. </b>
<code>bool timed</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int genpd_power_off(struct generic_pm_domain * genpd, bool one_dev_on, unsigned int depth)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
