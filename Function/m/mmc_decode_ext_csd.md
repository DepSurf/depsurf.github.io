# Function: <code>mmc_decode_ext_csd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585933819,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:339",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_read_ext_csd"
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
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586338703,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:358",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_read_ext_csd"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547264,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:360",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547264,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2793
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672912,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:364",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672912,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3281
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157280,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:364",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157280,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:364",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456560,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3268
    },
    {
      "addr": 18446744071587465222,
      "name": "mmc_decode_ext_csd.cold.23",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:365",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636768,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3241
    },
    {
      "addr": 18446744071587645446,
      "name": "mmc_decode_ext_csd.cold.23",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915648,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3309
    },
    {
      "addr": 18446744071587923958,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121568,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3309
    },
    {
      "addr": 18446744071588129873,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:361",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_read_ext_csd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985632,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2779
    },
    {
      "addr": 18446744071588992818,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:361",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_read_ext_csd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996816,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2807
    },
    {
      "addr": 18446744071591602375,
      "name": "mmc_decode_ext_csd.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:361",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588883952,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3050
    },
    {
      "addr": 18446744071591546022,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589586656,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3845
    },
    {
      "addr": 18446744071592663391,
      "name": "mmc_decode_ext_csd.cold",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:370",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591082544,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3731
    },
    {
      "addr": 18446744071594548593,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:370",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592799808,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3777
    },
    {
      "addr": 18446744071596316787,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:370",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593236336,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3935
    },
    {
      "addr": 18446744071596846165,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:382",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593991360,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3734
    },
    {
      "addr": 18446744071597771282,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501375672,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501375672,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2824
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233864928,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233864928,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2980
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294932992,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294932992,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3424
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277985746,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277985746,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2722
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587743136,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3309
    },
    {
      "addr": 18446744071587751441,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588076096,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3309
    },
    {
      "addr": 18446744071588084401,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```

```json
{
  "name": "mmc_decode_ext_csd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_decode_ext_csd",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:362",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193632,
      "name": "mmc_decode_ext_csd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3309
    },
    {
      "addr": 18446744071588201937,
      "name": "mmc_decode_ext_csd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
```
</details>
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
int mmc_decode_ext_csd(struct mmc_card * card, u8 * ext_csd)
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
