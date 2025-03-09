# Function: <code>wait_for_random_bytes</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584767072,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1549",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767072,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585187168,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1548",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:SyS_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187168,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585422944,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1653",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422944,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585546592,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1662",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546592,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585765984,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1744",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585765984,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585908336,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908336,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586656373,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1640",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_read"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648624,
      "name": "wait_for_random_bytes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071586648896,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586766917,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1639",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_read"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759264,
      "name": "wait_for_random_bytes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071586759536,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646585,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1615",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom",
        "drivers/char/random.c:random_read"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom",
        "drivers/char/random.c:random_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639856,
      "name": "wait_for_random_bytes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071586640304,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587193813,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1635",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_read"
      ],
      "caller_func": [
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186736,
      "name": "wait_for_random_bytes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071587187184,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:129",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read_iter",
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594323381,
      "name": "wait_for_random_bytes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071588495616,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589941104,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:132",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read_iter",
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941104,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590250384,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:132",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read_iter",
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250384,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590591376,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:132",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "crypto/rng.c:crypto_rng_reset",
        "drivers/char/random.c:random_read_iter",
        "drivers/char/random.c:__ia32_sys_getrandom",
        "drivers/char/random.c:__x64_sys_getrandom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590591376,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498732872,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498732872,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231356796,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231356796,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291887472,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291887472,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276240284,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276240284,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669328,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669328,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585529680,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529680,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585858736,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858736,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int wait_for_random_bytes()
```

```json
{
  "name": "wait_for_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585967104,
      "name": "wait_for_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1795",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_preparse",
        "crypto/rng.c:crypto_rng_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967104,
      "name": "wait_for_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
int wait_for_random_bytes()
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
