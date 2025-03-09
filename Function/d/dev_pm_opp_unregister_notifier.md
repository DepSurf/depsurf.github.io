# Function: <code>dev_pm_opp_unregister_notifier</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": false,
      "loc": "include/linux/pm_opp.h:226",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057488,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:1894",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057488,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353264,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:1785",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353264,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532960,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2009",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532960,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807104,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2126",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807104,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012128,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012128,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2358",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877260,
      "name": "dev_pm_opp_unregister_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588865920,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2456",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596271,
      "name": "dev_pm_opp_unregister_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588881600,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2830",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539234,
      "name": "dev_pm_opp_unregister_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588768704,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2840",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653442,
      "name": "dev_pm_opp_unregister_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589460208,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2980",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538120,
      "name": "dev_pm_opp_unregister_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590937840,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592640112,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2987",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592640112,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593070608,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:3001",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593070608,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593822128,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:3126",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593822128,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501268120,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501268120,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233758428,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233758428,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294789776,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294789776,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277944688,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277944688,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637120,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637120,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410992,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410992,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587968272,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968272,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_unregister_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588083648,
      "name": "dev_pm_opp_unregister_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2175",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_opp_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083648,
      "name": "dev_pm_opp_unregister_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int dev_pm_opp_unregister_notifier(struct device * dev, struct notifier_block * nb)
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
