# Function: <code>crypto_aead_encrypt</code>

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
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582902836,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
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
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583002580,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
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
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583052752,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
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
  "name": "crypto_aead_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582761091,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218374,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273107,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
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
  "name": "crypto_aead_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582961224,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426519,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478865,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:328",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
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
  "name": "crypto_aead_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583072268,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:325",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583547648,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:325",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602596,
      "name": "crypto_aead_encrypt",
      "external": false,
      "loc": "include/crypto/aead.h:325",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721232,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:87",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721232,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830912,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830912,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226640,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226640,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344992,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344992,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584379456,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379456,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774688,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774688,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585459584,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459584,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218368,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:83",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218368,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586455312,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:104",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455312,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721264,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:104",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721264,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495642304,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495642304,
      "name": "crypto_aead_encrypt",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228997892,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228997892,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289774032,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289774032,
      "name": "crypto_aead_encrypt",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274796816,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274796816,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799648,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799648,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736704,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736704,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783408,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783408,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
```

```json
{
  "name": "crypto_aead_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884432,
      "name": "crypto_aead_encrypt",
      "external": true,
      "loc": "crypto/aead.c:88",
      "file": "crypto/aead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_rfc4106_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884432,
      "name": "crypto_aead_encrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int crypto_aead_encrypt(struct aead_request * req)
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
