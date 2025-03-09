# Function: <code>clk_core_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082032,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:721",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_enable",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082032,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586492096,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:643",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586492096,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298816,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:643",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298816,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375936,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:643",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375936,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584782240,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:706",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782240,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585004848,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:864",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004848,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585111040,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:875",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111040,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316784,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:996",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316784,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585453408,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453408,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184592,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1008",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184592,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304224,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1002",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304224,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176784,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1002",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176784,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586674752,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1002",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674752,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945920,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1014",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945920,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589303856,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1098",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589303856,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589600928,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1140",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589600928,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589910704,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1140",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589910704,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497762144,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497762144,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230575916,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230575916,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275887146,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275887146,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215936,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215936,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168112,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168112,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403808,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403808,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int clk_core_enable(struct clk_core * core)
```

```json
{
  "name": "clk_core_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511248,
      "name": "clk_core_enable",
      "external": false,
      "loc": "drivers/clk/clk.c:1004",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511248,
      "name": "clk_core_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int clk_core_enable(struct clk_core * core)
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
