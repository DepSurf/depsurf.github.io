# Function: <code>__mmc_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, bool use_busy_signal, bool send_status, bool ignore_crc)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585948144,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:482",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc_ops.c:mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948144,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, bool use_busy_signal, bool send_status, bool ignore_crc)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353296,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:472",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353296,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562272,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:527",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562272,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686144,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:522",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686144,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587170576,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:523",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587170576,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:523",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587472684,
      "name": "__mmc_switch.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587470400,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:523",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587652808,
      "name": "__mmc_switch.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587650672,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930881,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587928752,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 889
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136785,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588134640,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:559",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588999948,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588998336,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:559",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603237,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589008160,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:539",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591546997,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588895504,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:564",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592664824,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589599632,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:594",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594550047,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591096368,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815072,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:594",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815072,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593251728,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:595",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593251728,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594006976,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:595",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594006976,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501387288,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501387288,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233876608,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233876608,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294947504,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294947504,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277996174,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277996174,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758353,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587756208,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091313,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588089168,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
```

```json
{
  "name": "__mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:525",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_hs400_to_hs200",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208849,
      "name": "__mmc_switch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588206704,
      "name": "__mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char timing</code>
</li>
<li>
<b>Param added. </b>
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param removed. </b>
<code>bool ignore_crc</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, set, index, value, timeout_ms, use_busy_signal, send_status, ignore_crc</code> ➡️ <code>card, set, index, value, timeout_ms, timing, use_busy_signal, send_status, retry_crc_err</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>bool use_busy_signal</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, set, index, value, timeout_ms, timing, use_busy_signal, send_status, retry_crc_err</code> ➡️ <code>card, set, index, value, timeout_ms, timing, send_status, retry_crc_err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int retries</code>
</li>
</ul>
</details>
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
int __mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err)
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
