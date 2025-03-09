# Function: <code>tpm_pcr_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234656,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:755",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234656,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574416,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:754",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574416,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756480,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:744",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756480,
      "name": "tpm_pcr_extend",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838464,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:901",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838464,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259296,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:919",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259296,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int tpm_pcr_extend(struct tpm_chip * chip, int pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585496112,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1040",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496112,
      "name": "tpm_pcr_extend",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, const u8 * hash)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620560,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:497",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620560,
      "name": "tpm_pcr_extend",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841264,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841264,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585983984,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983984,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725104,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725104,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820672,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820672,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700672,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700672,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250032,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250032,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558992,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558992,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590011776,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590011776,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590321056,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590321056,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590662448,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:314",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590662448,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498779064,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498779064,
      "name": "tpm_pcr_extend",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231393828,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231393828,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291969968,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291969968,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276273114,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276273114,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585744960,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585744960,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604144,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604144,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585934000,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585934000,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int tpm_pcr_extend(struct tpm_chip * chip, u32 pcr_idx, struct tpm_digest * digests)
```

```json
{
  "name": "tpm_pcr_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586041984,
      "name": "tpm_pcr_extend",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:313",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041984,
      "name": "tpm_pcr_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<code>struct tpm_digest * digests</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 * hash</code>
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
