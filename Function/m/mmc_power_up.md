# Function: <code>mmc_power_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585923088,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1710",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:_mmc_sd_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923088,
      "name": "mmc_power_up.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071585924736,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586328457,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1726",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327904,
      "name": "mmc_power_up.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071586329536,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586536803,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1796",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536240,
      "name": "mmc_power_up.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071586538032,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586659899,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1621",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659344,
      "name": "mmc_power_up.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 18446744071586660960,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587143608,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1835",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143024,
      "name": "mmc_power_up.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071587145216,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587442954,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1645",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_restore_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442560,
      "name": "mmc_power_up.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071587444064,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587626835,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1648",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587622992,
      "name": "mmc_power_up.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071587624176,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904261,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900368,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071587901616,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588110453,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105920,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588107168,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588972978,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1313",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967648,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588969344,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588985458,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1313",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980528,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588982240,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588872188,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1319",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868048,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588869760,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574604,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1320",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570224,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071592661291,
      "name": "mmc_power_up.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589572032,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591069530,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1320",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064848,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071594546409,
      "name": "mmc_power_up.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071591066720,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592783802,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1327",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592778640,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071596316220,
      "name": "mmc_power_up.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071592780592,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593220202,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1327",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593214976,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071596845627,
      "name": "mmc_power_up.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071593216912,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1332",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_select_voltage",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597770864,
      "name": "mmc_power_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071593970736,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501362176,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501356176,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446603336501357432,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233853332,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233848256,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 3233849472,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294916832,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294910176,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 13835058055294911872,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277974524,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277970622,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446743936277971770,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587732021,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727488,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071587728736,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588064981,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060448,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588061696,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
```

```json
{
  "name": "mmc_power_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182517,
      "name": "mmc_power_up",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1330",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_resume",
        "drivers/mmc/core/sd.c:mmc_sd_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177984,
      "name": "mmc_power_up.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071588179232,
      "name": "mmc_power_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mmc_power_up(struct mmc_host * host, u32 ocr)
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
