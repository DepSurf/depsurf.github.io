# Function: <code>tpm1_pcr_extend</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, int pcr_idx, const u8 * hash, char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838096,
      "name": "tpm1_pcr_extend",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:872",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838096,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int tpm1_pcr_extend(struct tpm_chip * chip, int pcr_idx, const u8 * hash, char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259072,
      "name": "tpm1_pcr_extend",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:890",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259072,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int tpm1_pcr_extend(struct tpm_chip * chip, int pcr_idx, const u8 * hash, char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495888,
      "name": "tpm1_pcr_extend",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:1009",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495888,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585624960,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:452",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624960,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585844992,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585844992,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585987552,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585987552,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728848,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728848,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824144,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824144,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704128,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704128,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587253792,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587253792,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562960,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562960,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590016736,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590016736,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590326032,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590326032,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590667424,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:463",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590667424,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498782944,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498782944,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231397556,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231397556,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291974912,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291974912,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276278070,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276278070,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748528,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748528,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607712,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607712,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585937568,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585937568,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int tpm1_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash, const char * log_msg)
```

```json
{
  "name": "tpm1_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045552,
      "name": "tpm1_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:448",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045552,
      "name": "tpm1_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int tpm1_pcr_extend(struct tpm_chip * chip, int pcr_idx, const u8 * hash, char * log_msg)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pcr_idx</code> ➡️ <code>u32 pcr_idx</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * log_msg</code> ➡️ <code>const char * log_msg</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
