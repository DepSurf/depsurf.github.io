# Function: <code>pinctrl_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162256,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1833",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162256,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583458976,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1845",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583458976,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583586704,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1845",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586704,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583625816,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2140",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625504,
      "name": "pinctrl_unregister.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071583625776,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583871928,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2149",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871616,
      "name": "pinctrl_unregister.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071583871888,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584072520,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2098",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072192,
      "name": "pinctrl_unregister.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071584072480,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158296,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2126",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157968,
      "name": "pinctrl_unregister.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071584158256,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584348248,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2115",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347920,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584348208,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584483064,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482736,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584483024,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585148184,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2139",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147840,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585148144,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585299496,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2162",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299152,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585299456,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585183400,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2186",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585183056,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585183360,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585636792,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2188",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585636448,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585636752,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586797352,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2188",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796976,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071586797296,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587933368,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2187",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932960,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071587933296,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588207512,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2196",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588207104,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071588207440,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588500328,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2210",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499920,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071588500256,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496501300,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496500808,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446603336496501224,
      "name": "pinctrl_unregister",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229807304,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229806832,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 3229807244,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290708004,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290707328,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 13835058055290707952,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275420124,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275419688,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446743936275420056,
      "name": "pinctrl_unregister",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451816,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451488,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584451776,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584387496,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387168,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584387456,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584434728,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434400,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584434688,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void pinctrl_unregister(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584540856,
      "name": "pinctrl_unregister",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2142",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540528,
      "name": "pinctrl_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071584540816,
      "name": "pinctrl_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
