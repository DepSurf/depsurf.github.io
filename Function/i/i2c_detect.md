# Function: <code>i2c_detect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585649516,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:2443",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586046220,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:2648",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586243788,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:2935",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586321968,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2121",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586321968,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586785632,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2145",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586785632,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587059248,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2131",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059248,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587218960,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2131",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587218960,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2224",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482688,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071587486429,
      "name": "i2c_detect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685952,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071587689628,
      "name": "i2c_detect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588554720,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2159",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554720,
      "name": "i2c_detect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588580176,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2289",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580176,
      "name": "i2c_detect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588463824,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2349",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463824,
      "name": "i2c_detect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589131920,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2350",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131920,
      "name": "i2c_detect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590581392,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2353",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590581392,
      "name": "i2c_detect.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592239024,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2361",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239024,
      "name": "i2c_detect.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592664128,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2474",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592664128,
      "name": "i2c_detect.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593409408,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2492",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593409408,
      "name": "i2c_detect.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500845936,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500845936,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233362984,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233362984,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294309152,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294309152,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277650178,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277650178,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637200,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071587640876,
      "name": "i2c_detect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_detect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_detect",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:2229",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:__process_new_driver",
        "drivers/i2c/i2c-core-base.c:__process_new_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748400,
      "name": "i2c_detect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071587752076,
      "name": "i2c_detect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_detect(struct i2c_adapter * adapter, struct i2c_driver * driver)
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
