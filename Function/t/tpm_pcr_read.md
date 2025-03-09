# Function: <code>tpm_pcr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584238000,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:720",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584238000,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577840,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:719",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577840,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759168,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:709",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759168,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841440,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:846",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841440,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(u32 chip_num, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585262064,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:864",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262064,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(struct tpm_chip * chip, int pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498944,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:984",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_init.c:ima_init",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498944,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, u8 * res_buf)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620464,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:467",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620464,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841152,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841152,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585983872,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983872,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586724992,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586724992,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820560,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820560,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700560,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700560,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587249920,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249920,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558864,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558864,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590011632,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590011632,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590320912,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590320912,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590662304,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:284",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm",
        "drivers/char/tpm/tpm-sysfs.c:pcr_value_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590662304,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498778928,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498778928,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231393712,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231393712,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291969776,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291969776,
      "name": "tpm_pcr_read",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276272998,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276272998,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585744848,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585744848,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604032,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604032,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585933888,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585933888,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int tpm_pcr_read(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digest)
```

```json
{
  "name": "tpm_pcr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586041872,
      "name": "tpm_pcr_read",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:283",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041872,
      "name": "tpm_pcr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip * chip</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 chip_num</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pcr_idx</code> ➡️ <code>u32 pcr_idx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_digest * digest</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 * res_buf</code>
</li>
</ul>
</details>
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
