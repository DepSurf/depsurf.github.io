# Function: <code>mmc_sd_setup_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952112,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:808",
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
      "addr": 18446744071585952112,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586357600,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:837",
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
      "addr": 18446744071586357600,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566752,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:846",
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
      "addr": 18446744071586566752,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1066
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586691584,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:833",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691584,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587177536,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:833",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177536,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:827",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479676,
      "name": "mmc_sd_setup_card.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587477104,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587657237,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:827",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659788,
      "name": "mmc_sd_setup_card.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071587657216,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587935335,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938052,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587935312,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588141239,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143979,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071588141216,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:871",
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
      "addr": 18446744071589007826,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589005120,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:901",
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
      "addr": 18446744071591604258,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589014704,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:909",
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
      "addr": 18446744071591547804,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071588902032,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:919",
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
      "addr": 18446744071592666087,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071589608240,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:926",
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
      "addr": 18446744071594551310,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071591106032,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:927",
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
      "addr": 18446744071596317309,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592826368,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:927",
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
      "addr": 18446744071596846693,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593262912,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:927",
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
      "addr": 18446744071597771810,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594018560,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 947
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501394320,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501394320,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233883340,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233883340,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294956832,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294956832,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278002418,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278002418,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587762807,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765547,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587762784,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588095767,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098507,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071588095744,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
```

```json
{
  "name": "mmc_sd_setup_card",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588213303,
      "name": "mmc_sd_setup_card",
      "external": true,
      "loc": "drivers/mmc/core/sd.c:847",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216043,
      "name": "mmc_sd_setup_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071588213280,
      "name": "mmc_sd_setup_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int mmc_sd_setup_card(struct mmc_host * host, struct mmc_card * card, bool reinit)
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
