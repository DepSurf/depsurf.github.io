# Function: <code>cpufreq_init_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263248,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2002",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263248,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586467632,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1974",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467632,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592336,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1977",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592336,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587075600,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2010",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075600,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2009",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373456,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071587377775,
      "name": "cpufreq_init_governor.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587553376,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2010",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553296,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071587557679,
      "name": "cpufreq_init_governor.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587828248,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2160",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828160,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587833246,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588033544,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033456,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071588038205,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588895276,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2211",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894656,
      "name": "cpufreq_init_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071588898959,
      "name": "cpufreq_init_governor.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907241,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2285",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588906448,
      "name": "cpufreq_init_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071591598244,
      "name": "cpufreq_init_governor.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588795401,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2291",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794176,
      "name": "cpufreq_init_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071591541770,
      "name": "cpufreq_init_governor.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589486509,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2293",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486464,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071592656884,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2333",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590967616,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071594541664,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2330",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592671728,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071596313993,
      "name": "cpufreq_init_governor.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2337",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593102544,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071596842914,
      "name": "cpufreq_init_governor.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2378",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855312,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071597768060,
      "name": "cpufreq_init_governor.cold",
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501300544,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501300544,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233788808,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233788808,
      "name": "cpufreq_init_governor",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294830864,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294830864,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587658536,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587658448,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587663197,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587432408,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432320,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587437069,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587989688,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989600,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587994349,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_init_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588105080,
      "name": "cpufreq_init_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2174",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588104992,
      "name": "cpufreq_init_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071588109773,
      "name": "cpufreq_init_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy * policy)
```
</details>
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
