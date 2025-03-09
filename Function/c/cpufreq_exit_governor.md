# Function: <code>cpufreq_exit_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586259839,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2046",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259312,
      "name": "cpufreq_exit_governor.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586466740,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2018",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586461360,
      "name": "cpufreq_exit_governor.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592956,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586585904,
      "name": "cpufreq_exit_governor.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587076273,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2054",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069200,
      "name": "cpufreq_exit_governor.part.23",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587366496,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2053",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366496,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587546384,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2054",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546384,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587820928,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2204",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820928,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588025824,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025824,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884928,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2255",
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
      "addr": 18446744071588884928,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588897648,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2331",
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
      "addr": 18446744071588897648,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588786496,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2337",
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
      "addr": 18446744071588786496,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589480000,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2339",
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
      "addr": 18446744071589479952,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071592656466,
      "name": "cpufreq_exit_governor.cold",
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590960496,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2379",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590960448,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071594541218,
      "name": "cpufreq_exit_governor.cold",
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592662912,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2376",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592662864,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071596313782,
      "name": "cpufreq_exit_governor.cold",
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593093632,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2383",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593093584,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071596842703,
      "name": "cpufreq_exit_governor.cold",
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593846368,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2424",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846320,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071597767849,
      "name": "cpufreq_exit_governor.cold",
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501288936,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501288936,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233782820,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233782820,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294821808,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294821808,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587650816,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650816,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424688,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424688,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587981968,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981968,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_exit_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588099568,
      "name": "cpufreq_exit_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2218",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099568,
      "name": "cpufreq_exit_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy * policy)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy * policy)
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
