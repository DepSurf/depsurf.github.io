# Function: <code>clk_fetch_parent_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586079424,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1065",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_core_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079424,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586487216,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1114",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586487216,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293936,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1114",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293936,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584373410,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1116",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584781349,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1193",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585009171,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1402",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585115277,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1508",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114304,
      "name": "clk_fetch_parent_index.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321699,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1626",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320192,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585458595,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456576,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176847,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1637",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586172544,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586296111,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1646",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291136,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586169360,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1667",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586164928,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586676711,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1667",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666560,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937488,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1681",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937488,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589294992,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1861",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294992,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590192,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1906",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590192,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589899744,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1906",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_hw_get_parent_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589899744,
      "name": "clk_fetch_parent_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497749736,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497746616,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230570732,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230569320,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275895378,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275891874,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585221123,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219104,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585173299,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171280,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585408995,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406976,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_fetch_parent_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585516531,
      "name": "clk_fetch_parent_index",
      "external": false,
      "loc": "drivers/clk/clk.c:1634",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_calc_new_rates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514464,
      "name": "clk_fetch_parent_index.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int clk_fetch_parent_index(struct clk_core * core, struct clk_core * parent)
```
</details>
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
