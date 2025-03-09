# Function: <code>dev_pm_opp_get_opp_table</code>

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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057712,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:842",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057712,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587356176,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:849",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587356176,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587538117,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:908",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_set_genpd_virt_dev",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536000,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587812005,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:982",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809856,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588017381,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588015040,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588875493,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1114",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588872752,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1201",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596189,
      "name": "dev_pm_opp_get_opp_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588881232,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1355",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539121,
      "name": "dev_pm_opp_get_opp_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588768176,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1365",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653360,
      "name": "dev_pm_opp_get_opp_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589459840,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1510",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594537989,
      "name": "dev_pm_opp_get_opp_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590937072,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592639600,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1482",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592639600,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593070096,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1498",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593070096,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593821408,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1609",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593821408,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501274860,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_provider_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501271856,
      "name": "dev_pm_opp_get_opp_table",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233764416,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_provider_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233761784,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294797580,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_provider_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294793792,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277950326,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_add_provider_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277947880,
      "name": "dev_pm_opp_get_opp_table",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587642373,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640032,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587416245,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413904,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587973525,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971184,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588088901,
      "name": "dev_pm_opp_get_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1031",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086560,
      "name": "dev_pm_opp_get_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct opp_table * dev_pm_opp_get_opp_table(struct device * dev)
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
