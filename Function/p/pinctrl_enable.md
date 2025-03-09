# Function: <code>pinctrl_enable</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583628624,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2048",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628624,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583874816,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2057",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874816,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2006",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078085,
      "name": "pinctrl_enable.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584075392,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584160105,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2034",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162677,
      "name": "pinctrl_enable.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584159968,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2023",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584352737,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071584349904,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487515,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584484752,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2047",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152837,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585151008,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2070",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591383402,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585302320,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2095",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325665,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585186320,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2095",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592346867,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585640208,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2095",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594208318,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586801168,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587937680,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2094",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937680,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588211920,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2103",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211920,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588504720,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2117",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588504720,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496502984,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496502984,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229808928,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229808928,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290714416,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290714416,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275421820,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275421820,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456267,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584453504,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391947,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584389184,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439179,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584436416,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_enable",
      "external": true,
      "loc": "drivers/pinctrl/core.c:2050",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584545307,
      "name": "pinctrl_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071584542544,
      "name": "pinctrl_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int pinctrl_enable(struct pinctrl_dev * pctldev)
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
