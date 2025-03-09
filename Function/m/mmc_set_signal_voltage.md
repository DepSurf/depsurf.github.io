# Function: <code>mmc_set_signal_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage, u32 ocr)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585925072,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1561",
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
      "addr": 18446744071585925072,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage, u32 ocr)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329856,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1577",
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
      "addr": 18446744071586329856,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage, u32 ocr)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586538352,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1649",
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
      "addr": 18446744071586538352,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586661614,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1465",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660432,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587144406,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1669",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144256,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587443254,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1468",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442208,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587623366,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1471",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587622640,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587900743,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900016,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588106295,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105568,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969968,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1136",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967296,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588982864,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1136",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980176,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588868887,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1142",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867696,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589571099,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1143",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569888,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591065722,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1143",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064432,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592779530,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1150",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592778144,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593215866,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1150",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593214496,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593969690,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1155",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593969136,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501356612,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501355776,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233848688,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233847868,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294910724,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294909520,
      "name": "mmc_set_signal_voltage",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277971102,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277970298,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587727863,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727136,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588060823,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060096,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
```

```json
{
  "name": "mmc_set_signal_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588178359,
      "name": "mmc_set_signal_voltage",
      "external": true,
      "loc": "drivers/mmc/core/core.c:1153",
      "file": "drivers/mmc/core/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_host_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage",
        "drivers/mmc/core/core.c:mmc_set_initial_signal_voltage"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177632,
      "name": "mmc_set_signal_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 ocr</code>
</li>
</ul>
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
int mmc_set_signal_voltage(struct mmc_host * host, int signal_voltage)
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
