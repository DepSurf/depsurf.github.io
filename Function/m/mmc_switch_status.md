# Function: <code>mmc_switch_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932112,
      "name": "mmc_switch_status",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1044",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932112,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586336992,
      "name": "mmc_switch_status",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:1004",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336992,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586562847,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:448",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562240,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586686452,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:443",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686112,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587170884,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:444",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587170544,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587470954,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:444",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470368,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587651226,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:444",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650640,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587929301,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587928720,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588135209,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588134608,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588998727,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:434",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998192,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589008551,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:434",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589008016,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588895925,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:413",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895360,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589600015,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:417",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589599456,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591096768,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591096160,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592815514,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592814832,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593252170,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593251584,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int mmc_switch_status(struct mmc_card * card, bool crc_err_fatal)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594007418,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594006832,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501387848,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501387240,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233877228,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233876576,
      "name": "mmc_switch_status",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294948096,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294947472,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277996562,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277996130,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587756777,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587756176,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588089737,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089136,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int mmc_switch_status(struct mmc_card * card)
```

```json
{
  "name": "mmc_switch_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588207273,
      "name": "mmc_switch_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:446",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588206672,
      "name": "mmc_switch_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool crc_err_fatal</code>
</li>
</ul>
</details>
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
int mmc_switch_status(struct mmc_card * card)
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
