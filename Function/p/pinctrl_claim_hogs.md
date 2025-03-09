# Function: <code>pinctrl_claim_hogs</code>

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
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583628641,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2009",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583874833,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2018",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584075397,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1967",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584159973,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1995",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584349909,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:1984",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584484757,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2009",
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
      "addr": 18446744071585150752,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071585152781,
      "name": "pinctrl_claim_hogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2032",
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
      "addr": 18446744071585302064,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071591383346,
      "name": "pinctrl_claim_hogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2057",
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
      "addr": 18446744071585186064,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071591325609,
      "name": "pinctrl_claim_hogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2057",
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
      "addr": 18446744071585639952,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071592346811,
      "name": "pinctrl_claim_hogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2057",
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
      "addr": 18446744071586800912,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071594208266,
      "name": "pinctrl_claim_hogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937360,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2056",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937360,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211600,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2065",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211600,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588504400,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2079",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588504400,
      "name": "pinctrl_claim_hogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496503012,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229808952,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290714456,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275421848,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584453509,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584389189,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584436421,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
  "name": "pinctrl_claim_hogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584542549,
      "name": "pinctrl_claim_hogs",
      "external": false,
      "loc": "drivers/pinctrl/core.c:2012",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable"
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
int pinctrl_claim_hogs(struct pinctrl_dev * pctldev)
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
