# Function: <code>mmc_set_data_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585911808,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:809",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585911808,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586311456,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:810",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586311456,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586519168,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:882",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519168,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644880,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:714",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644880,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587126624,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:868",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587126624,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426752,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:667",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426752,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607600,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:667",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607600,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885904,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885904,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092144,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092144,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588954144,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:648",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588954144,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966560,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:648",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966560,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588855104,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:649",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855104,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:649",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592660152,
      "name": "mmc_set_data_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589558160,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:649",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594545246,
      "name": "mmc_set_data_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071591052096,
      "name": "mmc_set_data_timeout",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:648",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596315551,
      "name": "mmc_set_data_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071592764592,
      "name": "mmc_set_data_timeout",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:648",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596844959,
      "name": "mmc_set_data_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071593200768,
      "name": "mmc_set_data_timeout",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:653",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597770055,
      "name": "mmc_set_data_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071593955344,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501340184,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501340184,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233833068,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233833068,
      "name": "mmc_set_data_timeout",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294889744,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294889744,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277957904,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277957904,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713712,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713712,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588046672,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588046672,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
```

```json
{
  "name": "mmc_set_data_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588164096,
      "name": "mmc_set_data_timeout",
      "external": true,
      "loc": "drivers/mmc/core/core.c:665",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588164096,
      "name": "mmc_set_data_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void mmc_set_data_timeout(struct mmc_data * data, const struct mmc_card * card)
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
