# Function: <code>clk_bulk_get</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584365104,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:32",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584365104,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770880,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:32",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770880,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584999504,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:32",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999504,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585104144,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:78",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585104144,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585308880,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:111",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308880,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446800,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446800,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586164320,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586164320,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281488,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281488,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586155264,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155264,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586656960,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586656960,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924848,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924848,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589279488,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589279488,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589576112,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589576112,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589885552,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589885552,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497735072,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497735072,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230558044,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230558044,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275879636,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275879636,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209328,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209328,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585161536,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585161536,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585397200,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397200,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
```

```json
{
  "name": "clk_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504544,
      "name": "clk_bulk_get",
      "external": true,
      "loc": "drivers/clk/clk-bulk.c:114",
      "file": "drivers/clk/clk-bulk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504544,
      "name": "clk_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int clk_bulk_get(struct device * dev, int num_clks, struct clk_bulk_data * clks)
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
