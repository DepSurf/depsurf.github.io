# Function: <code>tpm1_pcr_read</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585625552,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:575",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625552,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845824,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845824,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585988384,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988384,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586729616,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729616,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824912,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824912,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704896,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704896,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587254560,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254560,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563760,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563760,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590017568,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590017568,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590326864,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590326864,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590668256,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:584",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590668256,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498783888,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498783888,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231398592,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231398592,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291976160,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291976160,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276279446,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276279446,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749360,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749360,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608544,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608544,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585938400,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938400,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm1_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046368,
      "name": "tpm1_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:569",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046368,
      "name": "tpm1_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int tpm1_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```
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
