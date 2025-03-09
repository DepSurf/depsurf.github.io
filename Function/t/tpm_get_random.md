# Function: <code>tpm_get_random</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235888,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1021",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:pcrlock",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:trusted_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235888,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int tpm_get_random(u32 chip_num, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584575744,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1049",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575744,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int tpm_get_random(u32 chip_num, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757488,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1035",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757488,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int tpm_get_random(u32 chip_num, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839360,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1197",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839360,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int tpm_get_random(u32 chip_num, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260192,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1215",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260192,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1286",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499422,
      "name": "tpm_get_random.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585497008,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620992,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:615",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:pcrlock",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620992,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841616,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:436",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841616,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984304,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984304,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725440,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:441",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725440,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821008,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:441",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821008,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701008,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:441",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701008,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250368,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:441",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250368,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588559344,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:441",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588559344,
      "name": "tpm_get_random",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590012176,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:444",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012176,
      "name": "tpm_get_random",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590321504,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:454",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590321504,
      "name": "tpm_get_random",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590662896,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:454",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590662896,
      "name": "tpm_get_random",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498779440,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498779440,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231394176,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231394176,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291970512,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291970512,
      "name": "tpm_get_random",
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276273450,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276273450,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585745280,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745280,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604464,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604464,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585934320,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585934320,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int tpm_get_random(struct tpm_chip * chip, u8 * out, size_t max)
```

```json
{
  "name": "tpm_get_random",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042304,
      "name": "tpm_get_random",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:trusted_instantiate",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal",
        "drivers/char/tpm/tpm-chip.c:tpm_hwrng_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042304,
      "name": "tpm_get_random",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
