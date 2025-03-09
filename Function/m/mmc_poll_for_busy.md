# Function: <code>mmc_poll_for_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586562683,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:453",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586686600,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:448",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587171032,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:449",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587470772,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:449",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587651044,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:449",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587929125,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588135032,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588996168,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:539",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998304,
      "name": "mmc_poll_for_busy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589005992,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:539",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589008128,
      "name": "mmc_poll_for_busy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893375,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:518",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895472,
      "name": "mmc_poll_for_busy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589596230,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:515",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:sd_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589595936,
      "name": "mmc_poll_for_busy",
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
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591093488,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:544",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:sd_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591092624,
      "name": "mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592811889,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:544",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:sd_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592810000,
      "name": "mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593248641,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:544",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:sd_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593246768,
      "name": "mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594003793,
      "name": "mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:544",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend",
        "drivers/mmc/core/sd.c:mmc_sd_init_card",
        "drivers/mmc/core/sd.c:sd_flush_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594001920,
      "name": "mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501387648,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233876992,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294948048,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277996486,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587756600,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588089560,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588207096,
      "name": "mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:451",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, timeout_ms, busy_cmd</code> ➡️ <code>card, timeout_ms, retry_crc_err, busy_cmd</code>
</li>
</ul>
</details>
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
