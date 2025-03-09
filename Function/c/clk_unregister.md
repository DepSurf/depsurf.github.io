# Function: <code>clk_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083152,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:2654",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083152,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586494288,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:2688",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494288,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300992,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:2691",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300992,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584379168,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:2725",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379168,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584788032,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:2865",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788032,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3123",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023044,
      "name": "clk_unregister.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585017408,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3424",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130499,
      "name": "clk_unregister.cold.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585122240,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3767",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337048,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585330208,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475666,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585468272,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3965",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195611,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586187056,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4034",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444821,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586307152,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4043",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591385953,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586180320,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4070",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592423930,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071586682080,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4143",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594292063,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071587952736,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589313168,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4332",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589313168,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589610816,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4391",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589610816,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589920848,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:4437",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_unregister_cb",
        "drivers/clk/clk.c:devm_clk_unregister_cb",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589920848,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497764048,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite",
        "drivers/clk/imx/clk.c:imx_unregister_clocks",
        "drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll",
        "drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc",
        "drivers/clk/sunxi/clk-factors.c:sunxi_factors_unregister",
        "drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup",
        "drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe",
        "drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497764048,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230588796,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite",
        "drivers/clk/imx/clk.c:imx_unregister_clocks",
        "drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll",
        "drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/ti/clk.c:ti_clk_register",
        "drivers/clk/ti/composite.c:_register_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230588796,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275903424,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275903424,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238194,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585230800,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190370,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585182976,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426066,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585418672,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void clk_unregister(struct clk * clk)
```

```json
{
  "name": "clk_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_unregister",
      "external": true,
      "loc": "drivers/clk/clk.c:3875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:devm_clk_hw_release",
        "drivers/clk/clk.c:devm_clk_release",
        "drivers/clk/clk-divider.c:clk_unregister_divider",
        "drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor",
        "drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate",
        "drivers/clk/clk-gate.c:clk_unregister_gate",
        "drivers/clk/clk-mux.c:clk_unregister_mux",
        "drivers/clk/clk-composite.c:clk_unregister_composite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533986,
      "name": "clk_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071585526480,
      "name": "clk_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clk_unregister(struct clk * clk)
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
