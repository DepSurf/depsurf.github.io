# Function: <code>pinctrl_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583163184,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:870",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/pinctrl/core.c:pinctrl_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583163184,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583459936,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:883",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459936,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583587664,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:883",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583587664,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583628304,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1080",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628304,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583874496,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1080",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874496,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075072,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1080",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075072,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159648,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1108",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159648,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1084",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584352711,
      "name": "pinctrl_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584349600,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584484416,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484416,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585150368,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1113",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585150368,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585301680,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1114",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301680,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585185680,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1114",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185680,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585639584,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1114",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639584,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800480,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1114",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800480,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587936896,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1114",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936896,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211136,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1118",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211136,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503936,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1132",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503936,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496502608,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496502608,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229808572,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229808572,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290713904,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290713904,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275421472,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275421472,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584453168,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453168,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584388848,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388848,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584436080,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436080,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct pinctrl * pinctrl_get(struct device * dev)
```

```json
{
  "name": "pinctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584542208,
      "name": "pinctrl_get",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1112",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:devm_pinctrl_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542208,
      "name": "pinctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
