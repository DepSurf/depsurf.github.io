# Function: <code>clk_core_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586071261,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:163",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:__clk_is_enabled",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
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
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586492747,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:163",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:__clk_is_enabled",
        "drivers/clk/clk.c:clk_hw_is_enabled"
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
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584299467,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:163",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:__clk_is_enabled",
        "drivers/clk/clk.c:clk_hw_is_enabled"
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
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584376575,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:163",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:__clk_is_enabled",
        "drivers/clk/clk.c:clk_hw_is_enabled"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774816,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:192",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774816,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003296,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:207",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003296,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585109056,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:205",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109056,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314608,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:215",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314608,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452704,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452704,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169008,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:225",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169008,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287536,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:225",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_one",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287536,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161328,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:225",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161328,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:225",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664352,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071592423398,
      "name": "clk_core_is_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:218",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933344,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071594291594,
      "name": "clk_core_is_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:218",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589290640,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071596223794,
      "name": "clk_core_is_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:218",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled",
        "drivers/clk/clk.c:clk_core_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589587472,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071596751494,
      "name": "clk_core_is_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:218",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_summary_show_one",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled",
        "drivers/clk/clk.c:clk_core_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897024,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071597659129,
      "name": "clk_core_is_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497756008,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497756008,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230564648,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230564648,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275886254,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275886254,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215232,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215232,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167408,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167408,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403104,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403104,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
```

```json
{
  "name": "clk_core_is_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510496,
      "name": "clk_core_is_enabled",
      "external": false,
      "loc": "drivers/clk/clk.c:221",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_hw_is_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510496,
      "name": "clk_core_is_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool clk_core_is_enabled(struct clk_core * core)
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
bool clk_core_is_enabled(struct clk_core * core)
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
