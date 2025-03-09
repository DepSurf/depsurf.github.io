# Function: <code>clk_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586069768,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586480200,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584286904,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584365960,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584771736,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584999995,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:135",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585104747,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:132",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_get_sys"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585309664,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309664,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447584,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447584,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586164512,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586164512,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281584,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281584,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586155360,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155360,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586657056,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657056,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924960,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clkdev.c:clk_get",
        "drivers/clk/clkdev.c:clk_get_sys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924960,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589281019,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_find_hw"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589577640,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_find_hw"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589887080,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clkdev.c:clk_find_hw"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497736448,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497736448,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230559056,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230559056,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275880904,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275880904,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210112,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210112,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585162320,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162320,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585397984,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397984,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```

```json
{
  "name": "clk_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505328,
      "name": "clk_find",
      "external": false,
      "loc": "drivers/clk/clkdev.c:36",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clkdev.c:clk_find_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505328,
      "name": "clk_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
```
</details>
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
struct clk_lookup * clk_find(const char * dev_id, const char * con_id)
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
