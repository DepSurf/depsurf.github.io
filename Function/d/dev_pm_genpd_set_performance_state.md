# Function: <code>dev_pm_genpd_set_performance_state</code>

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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505936,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:256",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505936,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585750416,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:257",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750416,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585889904,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:378",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_genpd_virt_dev",
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889904,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:381",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133322,
      "name": "dev_pm_genpd_set_performance_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586126528,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275872,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275872,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587046112,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587046112,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130096,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:391",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130096,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016432,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:397",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016432,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587582080,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:435",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587582080,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920576,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:440",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920576,
      "name": "dev_pm_genpd_set_performance_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590432544,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:437",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:_set_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590432544,
      "name": "dev_pm_genpd_set_performance_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590752032,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:437",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_performance_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590752032,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589997856,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/pmdomain/core.c:455",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589997856,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499098624,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499098624,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231650052,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231650052,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292283680,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292283680,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276424986,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276424986,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039120,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039120,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585885136,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885136,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586225888,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225888,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
```

```json
{
  "name": "dev_pm_genpd_set_performance_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586335312,
      "name": "dev_pm_genpd_set_performance_state",
      "external": true,
      "loc": "drivers/base/power/domain.c:376",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table",
        "drivers/opp/core.c:_set_required_opps",
        "drivers/opp/core.c:_set_required_opps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586335312,
      "name": "dev_pm_genpd_set_performance_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int dev_pm_genpd_set_performance_state(struct device * dev, unsigned int state)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
