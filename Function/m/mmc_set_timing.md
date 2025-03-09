# Function: <code>mmc_set_timing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585924272,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1651",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585924272,
      "name": "mmc_set_timing",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329072,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1667",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329072,
      "name": "mmc_set_timing",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586537568,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1737",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537568,
      "name": "mmc_set_timing",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586660512,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1562",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660512,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587144752,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1776",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144752,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443600,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1586",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443600,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587623712,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1589",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587623712,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587901120,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901120,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106672,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106672,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968848,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1254",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968848,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588981744,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1254",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588981744,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588869264,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1260",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869264,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1261",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661418,
      "name": "mmc_set_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589571504,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1261",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594546532,
      "name": "mmc_set_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591066144,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1268",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596316343,
      "name": "mmc_set_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592779968,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1268",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596845750,
      "name": "mmc_set_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593216288,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1273",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597770800,
      "name": "mmc_set_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593970112,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501356920,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501356920,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233848996,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233848996,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294911152,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294911152,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277971340,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277971340,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587728240,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587728240,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061200,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061200,
      "name": "mmc_set_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
```

```json
{
  "name": "mmc_set_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588178736,
      "name": "mmc_set_timing",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1271",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588178736,
      "name": "mmc_set_timing",
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
void mmc_set_timing(struct mmc_host * host, unsigned int timing)
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
