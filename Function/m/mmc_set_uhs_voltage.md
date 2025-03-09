# Function: <code>mmc_set_uhs_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661280,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1481",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661280,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587145536,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1708",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145536,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1518",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447812,
      "name": "mmc_set_uhs_voltage.cold.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587444400,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1521",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587627924,
      "name": "mmc_set_uhs_voltage.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587624512,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905591,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587901904,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588111653,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588107456,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1186",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974124,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588969728,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1186",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591600733,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588982624,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1192",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591544371,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588870144,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1193",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661610,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071589572432,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1193",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594546717,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591067184,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592781248,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1200",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592781248,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593217552,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1200",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593217552,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593971568,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1205",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593971568,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501357872,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501357872,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233849836,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233849836,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294912448,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294912448,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277972322,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277972322,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587733221,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587729024,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588066181,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588061984,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_set_uhs_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_uhs_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1203",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:mmc_sd_get_cid",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183717,
      "name": "mmc_set_uhs_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588179520,
      "name": "mmc_set_uhs_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
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
int mmc_set_uhs_voltage(struct mmc_host * host, u32 ocr)
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
