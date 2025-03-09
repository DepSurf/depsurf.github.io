# Function: <code>mmc_remove_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585930160,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:367",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930160,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586334784,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586334784,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586543552,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543552,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666064,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:370",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666064,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150128,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:373",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150128,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:371",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449675,
      "name": "mmc_remove_card.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071587448992,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:371",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587629828,
      "name": "mmc_remove_card.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071587629104,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907655,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071587906880,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113618,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071588112832,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:382",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976178,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071588975392,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:394",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591601479,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071588987408,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:394",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591545093,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071588873808,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:392",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592662262,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071589576448,
      "name": "mmc_remove_card",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:382",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594547454,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071591071456,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:380",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596316586,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592786656,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:380",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596845987,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593223040,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:383",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597771083,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593977888,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501365976,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501365976,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233856072,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233856072,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294920672,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294920672,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277976974,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277976974,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735186,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071587734400,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068146,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071588067360,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
```

```json
{
  "name": "mmc_remove_card",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_remove_card",
      "external": true,
      "loc": "drivers/mmc/core/bus.c:368",
      "file": "drivers/mmc/core/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_remove",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185682,
      "name": "mmc_remove_card.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071588184896,
      "name": "mmc_remove_card",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void mmc_remove_card(struct mmc_card * card)
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
