# Function: <code>mmc_detach_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926064,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1847",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926064,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586330848,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1863",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330848,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539376,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1928",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539376,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662160,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1753",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662160,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587146048,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1967",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587146048,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444880,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1771",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444880,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587624992,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1774",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587624992,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905698,
      "name": "mmc_detach_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587902400,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588107952,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107952,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588970624,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1439",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588970624,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983520,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1439",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983520,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588872341,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1395",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588870544,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574837,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1396",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572832,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591069756,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1396",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067600,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592784060,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1403",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592781744,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593220460,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1403",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593218048,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593975228,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1408",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_stop_host"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593972816,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501358512,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501358512,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233850476,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233850476,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294913216,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294913216,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277972778,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277972778,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587729520,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587729520,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588062480,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062480,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mmc_detach_bus(struct mmc_host * host)
```

```json
{
  "name": "mmc_detach_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588180016,
      "name": "mmc_detach_bus",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1456",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/mmc.c:mmc_attach_mmc",
        "drivers/mmc/core/sd.c:mmc_attach_sd",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180016,
      "name": "mmc_detach_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void mmc_detach_bus(struct mmc_host * host)
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
