# Function: <code>__mmc_poll_for_busy</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:488",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588995584,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071588999857,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int __mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:488",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005408,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071591603146,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int __mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": false,
      "loc": "drivers/mmc/core/mmc_ops.c:467",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892720,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071591546829,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int __mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, int (*)(void *, bool *) busy_cb, void * cb_data)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:473",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592664492,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071589595664,
      "name": "__mmc_poll_for_busy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_poll_for_busy(struct mmc_host * host, unsigned int period_us, unsigned int timeout_ms, int (*)(void *, bool *) busy_cb, void * cb_data)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:502",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594549762,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071591092336,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __mmc_poll_for_busy(struct mmc_host * host, unsigned int period_us, unsigned int timeout_ms, int (*)(void *, bool *) busy_cb, void * cb_data)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:502",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596317087,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071592809632,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int __mmc_poll_for_busy(struct mmc_host * host, unsigned int period_us, unsigned int timeout_ms, int (*)(void *, bool *) busy_cb, void * cb_data)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:502",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596846465,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071593246400,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int __mmc_poll_for_busy(struct mmc_host * host, unsigned int period_us, unsigned int timeout_ms, int (*)(void *, bool *) busy_cb, void * cb_data)
```

```json
{
  "name": "__mmc_poll_for_busy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_poll_for_busy",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:502",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/sd.c:_mmc_sd_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597771582,
      "name": "__mmc_poll_for_busy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071594001552,
      "name": "__mmc_poll_for_busy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __mmc_poll_for_busy(struct mmc_card * card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd)
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
<code>int (*)(void *, bool *) busy_cb</code>
</li>
<li>
<b>Param added. </b>
<code>void * cb_data</code>
</li>
<li>
<b>Param removed. </b>
<code>bool send_status</code>
</li>
<li>
<b>Param removed. </b>
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param removed. </b>
<code>enum mmc_busy_cmd busy_cmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_host * host</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int period_us</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmc_card * card</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, timeout_ms, busy_cb, cb_data</code> ➡️ <code>host, period_us, timeout_ms, busy_cb, cb_data</code>
</li>
</ul>
</details>
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
