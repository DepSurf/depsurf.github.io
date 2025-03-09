# Function: <code>mmc_send_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946368,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:86",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/mmc.c:mmc_switch_status",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946368,
      "name": "mmc_send_status",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586351488,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:86",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/mmc.c:mmc_switch_status",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586351488,
      "name": "mmc_send_status",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586560256,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:57",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/core.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560256,
      "name": "mmc_send_status",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586687579,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:82",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684368,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587172429,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:82",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587166592,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587472129,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:82",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466480,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587652321,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:82",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646752,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587930401,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924944,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588136305,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130832,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589000082,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:80",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996480,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591603371,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:80",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589006304,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893219,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:80",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893888,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589596082,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:85",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589597344,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591093334,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:93",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591093744,
      "name": "mmc_send_status",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592811739,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:93",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592812192,
      "name": "mmc_send_status",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593248491,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:93",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593248944,
      "name": "mmc_send_status",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594003643,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:93",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004096,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501389124,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501383192,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233878472,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233872668,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294949968,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294942352,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277997634,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277992630,
      "name": "mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587757873,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752400,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588090833,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085360,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
```

```json
{
  "name": "mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208369,
      "name": "mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:78",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_alive",
        "drivers/mmc/core/sd.c:mmc_sd_alive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202896,
      "name": "mmc_send_status",
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
int mmc_send_status(struct mmc_card * card, u32 * status)
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
