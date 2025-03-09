# Function: <code>crypto_xor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void crypto_xor(u8 * dst, const u8 * src, unsigned int size)
```

```json
{
  "name": "crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634416,
      "name": "crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:972",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634416,
      "name": "crypto_xor",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void crypto_xor(u8 * dst, const u8 * src, unsigned int size)
```

```json
{
  "name": "crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883968,
      "name": "crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:981",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883968,
      "name": "crypto_xor",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void crypto_xor(u8 * dst, const u8 * src, unsigned int size)
```

```json
{
  "name": "crypto_xor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980544,
      "name": "crypto_xor",
      "external": true,
      "loc": "crypto/algapi.c:982",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980544,
      "name": "crypto_xor",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583052733,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094581,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096632,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583103234,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
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
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583218355,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261112,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263193,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269893,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273569,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306727,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:197",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583426499,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468425,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583470986,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477124,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480829,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:204",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583547628,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590409,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583593066,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583598052,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600989,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:206",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583736913,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583778426,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780865,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583784981,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788541,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583846673,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880170,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583882630,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583887893,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891485,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584235553,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584270960,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272693,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584277805,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281085,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584354096,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584389682,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391589,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584396493,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584399741,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584388497,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424249,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584425957,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584430821,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584434029,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:139",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584783729,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821561,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823269,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828181,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831389,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:147",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585469026,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512831,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514844,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585520219,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585524045,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:152",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586228962,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586272757,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275148,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586280939,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586285277,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:161",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586464562,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516645,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519052,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524939,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586529357,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586736370,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586786650,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_inplace",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_decrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_inplace",
        "crypto/cbc.c:crypto_cbc_encrypt_segment",
        "crypto/cbc.c:crypto_cbc_encrypt_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789004,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586795179,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586798013,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/utils.h:16",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495660156,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495698576,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495701184,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495706544,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495711424,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229014216,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229052928,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229054968,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229060356,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229066184,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3229096888,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289797344,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289845732,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289849160,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289856336,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289862196,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274812094,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274848610,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274849392,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274854758,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274858458,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274892298,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583815409,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848906,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851366,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856629,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860221,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583752465,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785962,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788422,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793685,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797277,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583799169,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832666,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583835126,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840389,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843981,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_xor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583900193,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933738,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936198,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583941461,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945053,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_xor",
      "external": false,
      "loc": "include/crypto/algapi.h:200",
      "file": "crypto/ghash-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ghash-generic.c:ghash_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void crypto_xor(u8 * dst, const u8 * src, unsigned int size)
```
</details>
</li>
</ul>
