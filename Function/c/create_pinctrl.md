# Function: <code>create_pinctrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583163348,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:790",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583460093,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:803",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583587821,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:803",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_get"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627312,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:991",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627312,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873504,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:991",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873504,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074112,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:991",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074112,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158688,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1019",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158688,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:995",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348656,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584352686,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483472,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584487490,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149872,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1024",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149872,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585301184,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1025",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301184,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585185184,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1025",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185184,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585639088,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1025",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639088,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799984,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1025",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799984,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587936384,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1026",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936384,
      "name": "create_pinctrl",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588210624,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1030",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210624,
      "name": "create_pinctrl",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503376,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1044",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503376,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496501680,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496501680,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229807600,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229807600,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290711328,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290711328,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2572
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275420622,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275420622,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452224,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584456242,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387904,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584391922,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435136,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584439154,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
```

```json
{
  "name": "create_pinctrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_pinctrl",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541264,
      "name": "create_pinctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071584545282,
      "name": "create_pinctrl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct pinctrl * create_pinctrl(struct device * dev, struct pinctrl_dev * pctldev)
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
