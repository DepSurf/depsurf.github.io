# Function: <code>mmc_decode_cid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585939194,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:65",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585950528,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:73",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950528,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586345685,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:76",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355984,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:73",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355984,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586553947,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:78",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565136,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:73",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565136,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586677964,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:70",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586690096,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:75",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690096,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587162313,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:70",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587176048,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:75",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176048,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587461886,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:70",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476096,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:75",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476096,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587642066,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:71",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587656208,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:75",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656208,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587920536,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933984,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933984,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588126463,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588139888,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139888,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588989750,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589004384,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004384,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589000966,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589013968,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589013968,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588888197,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901296,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588901296,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589592359,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:69",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589607584,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:80",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589607584,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591088000,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:71",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591105264,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:83",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591105264,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592805474,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:71",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592825424,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:83",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592825424,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593242151,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:71",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593262000,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:83",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593262000,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593997165,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:71",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594017600,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:83",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017600,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501379800,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501392936,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501392936,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233869336,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 3233881980,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233881980,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294937916,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294955056,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294955056,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277989626,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278001062,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278001062,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748031,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587761456,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761456,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588080991,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588094416,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094416,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int mmc_decode_cid(struct mmc_card * card)
```

```json
{
  "name": "mmc_decode_cid",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588198527,
      "name": "mmc_decode_cid",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:68",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211952,
      "name": "mmc_decode_cid",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:72",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211952,
      "name": "mmc_decode_cid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int mmc_decode_cid(struct mmc_card * card)
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
