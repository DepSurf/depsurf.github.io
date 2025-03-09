# Function: <code>clk_recalc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586072374,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:987",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_recalc_rates",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:clk_change_rate"
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
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586496567,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1036",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
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
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584303255,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1036",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584381717,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1038",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584780128,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1111",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780128,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585007888,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1320",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007888,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585114608,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1426",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114608,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321008,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1544",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321008,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585457904,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457904,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176144,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1556",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176144,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586295408,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1565",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295408,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586168640,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1586",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168640,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586675992,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1586",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586675952,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071592423768,
      "name": "clk_recalc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587946472,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1600",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946432,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071594291876,
      "name": "clk_recalc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589304744,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1775",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304704,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071596223905,
      "name": "clk_recalc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589601368,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1820",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601328,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071596751605,
      "name": "clk_recalc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589911144,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1820",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589911104,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071597659240,
      "name": "clk_recalc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497748904,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497748904,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230569936,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230569936,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275894680,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275894680,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585220432,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220432,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585172608,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172608,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585408304,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408304,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
```

```json
{
  "name": "clk_recalc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585515840,
      "name": "clk_recalc",
      "external": false,
      "loc": "drivers/clk/clk.c:1552",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_subtree",
        "drivers/clk/clk.c:__clk_speculate_rates",
        "drivers/clk/clk.c:__clk_recalc_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515840,
      "name": "clk_recalc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int clk_recalc(struct clk_core * core, long unsigned int parent_rate)
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
