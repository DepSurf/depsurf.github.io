# Function: <code>crypto_aead_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582902333,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583002077,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
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
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583052221,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
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
  "name": "crypto_aead_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582761112,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217821,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273247,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:355",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
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
  "name": "crypto_aead_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582961140,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:360",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425949,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:360",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478749,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:360",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
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
  "name": "crypto_aead_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583072154,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:363",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546979,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:363",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602456,
      "name": "crypto_aead_decrypt",
      "external": false,
      "loc": "include/crypto/aead.h:363",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721344,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:104",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721344,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831024,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831024,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226752,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226752,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584345104,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345104,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584379568,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379568,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774800,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774800,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585459696,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459696,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218496,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:100",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218496,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586455184,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:127",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455184,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721136,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:127",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721136,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495642424,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495642424,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228998000,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228998000,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289774224,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289774224,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274796926,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274796926,
      "name": "crypto_aead_decrypt",
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799760,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799760,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736816,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736816,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783520,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783520,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int crypto_aead_decrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884544,
      "name": "crypto_aead_decrypt",
      "external": true,
      "loc": "crypto/aead.c:105",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884544,
      "name": "crypto_aead_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int crypto_aead_decrypt(struct aead_request * req)
```
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
