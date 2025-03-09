# Function: <code>mmc_read_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585952536,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:280",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586358015,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:278",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586567173,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:278",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586691992,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:280",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_read_switch(struct mmc_card * card)
```

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587174224,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:280",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587174224,
      "name": "mmc_read_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int mmc_read_switch(struct mmc_card * card)
```

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:280",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474160,
      "name": "mmc_read_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071587479287,
      "name": "mmc_read_switch.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int mmc_read_switch(struct mmc_card * card)
```

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587654282,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:280",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654240,
      "name": "mmc_read_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071587659399,
      "name": "mmc_read_switch.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587936397,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932336,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071587937646,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588142301,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138240,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588143573,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589006007,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002912,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071589007495,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589015591,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012496,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071591603927,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588902919,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:306",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899696,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071591547437,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589609155,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:316",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589603968,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071592665344,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int mmc_read_switch(struct mmc_card * card)
```

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591101355,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:325",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591101312,
      "name": "mmc_read_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071594550578,
      "name": "mmc_read_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592826405,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:325",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593262949,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:325",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594018597,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:325",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_setup_card"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501395532,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501391200,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233884520,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233880268,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294958472,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294952656,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278003472,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277999524,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587763869,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587759808,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071587765141,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588096829,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092768,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588098101,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_read_switch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588214365,
      "name": "mmc_read_switch",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:300",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210304,
      "name": "mmc_read_switch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588215637,
      "name": "mmc_read_switch.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int mmc_read_switch(struct mmc_card * card)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int mmc_read_switch(struct mmc_card * card)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int mmc_read_switch(struct mmc_card * card)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int mmc_read_switch(struct mmc_card * card)
```
</details>
</li>
</ul>
