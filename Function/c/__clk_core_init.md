# Function: <code>__clk_core_init</code>

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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586499419,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:2323",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584306107,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:2318",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584384977,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:2351",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584791668,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:2468",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585021054,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:2725",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585128542,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3021",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_register"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3209",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330704,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    },
    {
      "addr": 18446744071585337137,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470928,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071585475806,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3342",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187904,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
    },
    {
      "addr": 18446744071586195700,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3393",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308000,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
    },
    {
      "addr": 18446744071591444910,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3406",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180992,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071591386042,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3424",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682752,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
    },
    {
      "addr": 18446744071592424019,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3499",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953440,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    },
    {
      "addr": 18446744071594292152,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3689",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589314048,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1896
    },
    {
      "addr": 18446744071596224052,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3734",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589611696,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1831
    },
    {
      "addr": 18446744071596751752,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3780",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589921728,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1831
    },
    {
      "addr": 18446744071597659408,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497767944,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497767944,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230585332,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230585332,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275906836,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275906836,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233456,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071585238334,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185632,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071585190510,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421328,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071585426206,
      "name": "__clk_core_init.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __clk_core_init(struct clk_core * core)
```

```json
{
  "name": "__clk_core_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_core_init",
      "external": false,
      "loc": "drivers/clk/clk.c:3269",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:__clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529248,
      "name": "__clk_core_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071585534126,
      "name": "__clk_core_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int __clk_core_init(struct clk_core * core)
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
int __clk_core_init(struct clk_core * core)
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
