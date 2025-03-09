# Function: <code>mmc_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585923840,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1750",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923840,
      "name": "mmc_power_off.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585924768,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586331258,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1766",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328656,
      "name": "mmc_power_off.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586329568,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539834,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1836",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537072,
      "name": "mmc_power_off.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586538064,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586662522,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1661",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660096,
      "name": "mmc_power_off.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586660992,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587146427,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1875",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143856,
      "name": "mmc_power_off.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587145248,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587445259,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1679",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_power_save_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441808,
      "name": "mmc_power_off.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587444096,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587625371,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1682",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587622560,
      "name": "mmc_power_off.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587624208,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587902771,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899728,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587901648,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588108467,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105296,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588107200,
      "name": "mmc_power_off",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588971071,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1347",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969376,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588983857,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1347",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588982272,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588872362,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1353",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869792,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574858,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1354",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572064,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591069774,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1354",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591066768,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592784078,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1361",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592780656,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593220478,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1361",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593216976,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593975246,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1366",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_rescan_try_freq",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_select_voltage",
        "drivers/mmc/core/core.c:mmc_select_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593972512,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501359260,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501355232,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336501357496,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233851016,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233847364,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3233849512,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294913848,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294908752,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 13835058055294911904,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277974756,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277969906,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446743936277971830,
      "name": "mmc_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587730035,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726864,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071587728768,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588062995,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059824,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588061728,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
```

```json
{
  "name": "mmc_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588180531,
      "name": "mmc_power_off",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1364",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_power_cycle",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177360,
      "name": "mmc_power_off.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071588179264,
      "name": "mmc_power_off",
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
void mmc_power_off(struct mmc_host * host)
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
