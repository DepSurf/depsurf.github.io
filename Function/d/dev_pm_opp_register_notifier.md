# Function: <code>dev_pm_opp_register_notifier</code>

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
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": false,
      "loc": "include/linux/pm_opp.h:221",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057408,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:1870",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057408,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353184,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:1761",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353184,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532880,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:1985",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532880,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807024,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807024,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012048,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012048,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2334",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877229,
      "name": "dev_pm_opp_register_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588865760,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2432",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596302,
      "name": "dev_pm_opp_register_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588881760,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2806",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539203,
      "name": "dev_pm_opp_register_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588768544,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2816",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653473,
      "name": "dev_pm_opp_register_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589460368,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2956",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538089,
      "name": "dev_pm_opp_register_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590937664,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592640320,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2963",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592640320,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593070816,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2977",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593070816,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593821920,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:3102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593821920,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501268008,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501268008,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233758352,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233758352,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294789616,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294789616,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277944586,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277944586,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637040,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637040,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410912,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410912,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587968192,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968192,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
```

```json
{
  "name": "dev_pm_opp_register_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588083568,
      "name": "dev_pm_opp_register_notifier",
      "external": true,
      "loc": "drivers/opp/core.c:2151",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083568,
      "name": "dev_pm_opp_register_notifier",
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
int dev_pm_opp_register_notifier(struct device * dev, struct notifier_block * nb)
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
