# Function: <code>tpm_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235360,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:845",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:oiap",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235360,
      "name": "tpm_send",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584575136,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:873",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575136,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int tpm_send(u32 chip_num, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756864,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:858",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756864,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int tpm_send(u32 chip_num, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838912,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1022",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838912,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int tpm_send(u32 chip_num, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259744,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1040",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259744,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585496560,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1172",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:oiap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496560,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623408,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:538",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:oiap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623408,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843072,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:348",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843072,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585985760,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985760,
      "name": "tpm_send",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586726768,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726768,
      "name": "tpm_send",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822336,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822336,
      "name": "tpm_send",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702320,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702320,
      "name": "tpm_send",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587251696,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251696,
      "name": "tpm_send",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588560800,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588560800,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590014016,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590014016,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323328,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323328,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590664720,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:353",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664720,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498780848,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498780848,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231395532,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231395532,
      "name": "tpm_send",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291972432,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291972432,
      "name": "tpm_send",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276274992,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276274992,
      "name": "tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585746736,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746736,
      "name": "tpm_send",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585605920,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605920,
      "name": "tpm_send",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585935776,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935776,
      "name": "tpm_send",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip * chip, void * cmd, size_t buflen)
```

```json
{
  "name": "tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043760,
      "name": "tpm_send",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:352",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043760,
      "name": "tpm_send",
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
