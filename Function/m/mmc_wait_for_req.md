# Function: <code>mmc_wait_for_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585920032,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:650",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
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
      "addr": 18446744071585920032,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586324115,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:651",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324000,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532640,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:724",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532640,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654384,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:668",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654384,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136544,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:822",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136544,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436592,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436592,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616784,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616784,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587894352,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587894352,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588099904,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099904,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961808,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:602",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961808,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973504,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:602",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973504,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862096,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:603",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862096,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:603",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592660513,
      "name": "mmc_wait_for_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589564128,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:603",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594545610,
      "name": "mmc_wait_for_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591059344,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:602",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596315843,
      "name": "mmc_wait_for_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592772320,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:602",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596845250,
      "name": "mmc_wait_for_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593208800,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:607",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597770346,
      "name": "mmc_wait_for_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593963376,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501349512,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501349512,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233841124,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233841124,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294900912,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294900912,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277966064,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277966064,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587721472,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721472,
      "name": "mmc_wait_for_req",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054432,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054432,
      "name": "mmc_wait_for_req",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
```

```json
{
  "name": "mmc_wait_for_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171968,
      "name": "mmc_wait_for_req",
      "external": true,
      "loc": "drivers/mmc/core/core.c:619",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_wait_for_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_bus_test",
        "drivers/mmc/core/mmc_ops.c:mmc_send_tuning",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data",
        "drivers/mmc/core/sd_ops.c:mmc_app_sd_status",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch",
        "drivers/mmc/core/sd_ops.c:mmc_app_send_scr",
        "drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171968,
      "name": "mmc_wait_for_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void mmc_wait_for_req(struct mmc_host * host, struct mmc_request * mrq)
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
