# Function: <code>mmc_select_driver_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585939626,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1219",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
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
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586345770,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1323",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
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
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586554032,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1350",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
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
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586679320,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1377",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587155136,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1291",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155136,
      "name": "mmc_select_driver_type",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587454528,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1297",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587454528,
      "name": "mmc_select_driver_type",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587634768,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1310",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634768,
      "name": "mmc_select_driver_type",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912752,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912752,
      "name": "mmc_select_driver_type",
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588118640,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118640,
      "name": "mmc_select_driver_type",
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588982960,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1312",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588982960,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588994128,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1319",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994128,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880912,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1319",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880912,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1322",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589583808,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071592662857,
      "name": "mmc_select_driver_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1337",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591079472,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071594548108,
      "name": "mmc_select_driver_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1337",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592796192,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071596316637,
      "name": "mmc_select_driver_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1337",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593232704,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071596846029,
      "name": "mmc_select_driver_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1347",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987504,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071597771125,
      "name": "mmc_select_driver_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501372408,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501372408,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233861840,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233861840,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294928816,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294928816,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277983002,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277983002,
      "name": "mmc_select_driver_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587740208,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740208,
      "name": "mmc_select_driver_type",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588073168,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073168,
      "name": "mmc_select_driver_type",
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
void mmc_select_driver_type(struct mmc_card * card)
```

```json
{
  "name": "mmc_select_driver_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190704,
      "name": "mmc_select_driver_type",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1307",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190704,
      "name": "mmc_select_driver_type",
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
void mmc_select_driver_type(struct mmc_card * card)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void mmc_select_driver_type(struct mmc_card * card)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
