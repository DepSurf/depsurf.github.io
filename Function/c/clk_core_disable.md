# Function: <code>clk_core_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081632,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:673",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081632,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586491568,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:587",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586491568,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584298288,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:587",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298288,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369568,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:587",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369568,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775952,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:650",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775952,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585004448,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:807",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004448,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110512,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:818",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110512,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316256,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:939",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316256,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452976,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452976,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586183728,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:951",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586183728,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303408,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:945",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303408,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173952,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:945",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173952,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672272,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:945",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672272,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587944288,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:957",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944288,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302272,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:1041",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302272,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598944,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:1083",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598944,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589908720,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:1083",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_disable",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589908720,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497760336,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497760336,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230575164,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230575164,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275886670,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275886670,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215504,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215504,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167680,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167680,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403376,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403376,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void clk_core_disable(struct clk_core * core)
```

```json
{
  "name": "clk_core_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510768,
      "name": "clk_core_disable",
      "external": false,
      "loc": "drivers/clk/clk.c:947",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable_lock",
        "drivers/clk/clk.c:clk_core_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510768,
      "name": "clk_core_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void clk_core_disable(struct clk_core * core)
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
