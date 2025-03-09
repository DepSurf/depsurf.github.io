# Function: <code>__mmc_send_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __mmc_send_status(struct mmc_card * card, u32 * status, bool ignore_crc)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585945120,
      "name": "__mmc_send_status",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:57",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_status",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945120,
      "name": "__mmc_send_status.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071585945136,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int __mmc_send_status(struct mmc_card * card, u32 * status, bool ignore_crc)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586351497,
      "name": "__mmc_send_status",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:57",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_status"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350240,
      "name": "__mmc_send_status.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071586350256,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682000,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:58",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682000,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587166432,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:58",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587166432,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466320,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:58",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466320,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646592,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:58",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646592,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924800,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924800,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588130688,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130688,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588993520,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:56",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993520,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589003360,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:56",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589003360,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588890672,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:56",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890672,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589594464,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:61",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594464,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591090496,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:69",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591090496,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592808512,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:69",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592808512,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593245280,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:69",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593245280,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594000432,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:69",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_busy_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594000432,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501383016,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:card_busy_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501383016,
      "name": "__mmc_send_status",
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233872488,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:card_busy_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233872488,
      "name": "__mmc_send_status",
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294942128,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294942128,
      "name": "__mmc_send_status",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277992490,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:card_busy_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277992490,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587752256,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752256,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085216,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085216,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```

```json
{
  "name": "__mmc_send_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202752,
      "name": "__mmc_send_status",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:54",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202752,
      "name": "__mmc_send_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int __mmc_send_status(struct mmc_card * card, u32 * status, bool ignore_crc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
```
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
int __mmc_send_status(struct mmc_card * card, u32 * status, unsigned int retries)
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
