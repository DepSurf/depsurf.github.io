# Function: <code>crypto_drop_spawn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635136,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:641",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/blkcipher.c:skcipher_geniv_free",
        "crypto/blkcipher.c:skcipher_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635136,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582884672,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:640",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884672,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981248,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:641",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981248,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583034832,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:641",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034832,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583200144,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:653",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583200144,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583408256,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:650",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408256,
      "name": "crypto_drop_spawn",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583527488,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:659",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/ecb.c:crypto_ecb_free",
        "crypto/cbc.c:crypto_cbc_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/ctr.c:crypto_ctr_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527488,
      "name": "crypto_drop_spawn",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583715152,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:670",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715152,
      "name": "crypto_drop_spawn",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822464,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822464,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584218432,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:702",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218432,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336816,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:704",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336816,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584371344,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:704",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371344,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584766474,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:704",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592310271,
      "name": "crypto_drop_spawn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584766448,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585451322,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:728",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092808,
      "name": "crypto_drop_spawn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585451296,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586208426,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:747",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103390,
      "name": "crypto_drop_spawn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586208400,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586446650,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:759",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596626495,
      "name": "crypto_drop_spawn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586446624,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586712506,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:760",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/lskcipher.c:lskcipher_alloc_instance_simple",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/shash.c:shash_free_singlespawn_instance",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/dh.c:__dh_safe_prime_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/ecb.c:lskcipher_alloc_instance_simple2",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:xts_create",
        "crypto/xts.c:xts_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597532179,
      "name": "crypto_drop_spawn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586712480,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495629984,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495629984,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228987688,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228987688,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289754864,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289754864,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274787804,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274787804,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791200,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791200,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728256,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728256,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774960,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774960,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void crypto_drop_spawn(struct crypto_spawn * spawn)
```

```json
{
  "name": "crypto_drop_spawn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875952,
      "name": "crypto_drop_spawn",
      "external": true,
      "loc": "crypto/algapi.c:688",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:aead_geniv_free",
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_free_instance_simple",
        "crypto/ahash.c:ahash_free_instance",
        "crypto/shash.c:shash_free_instance",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_free",
        "crypto/cts.c:crypto_cts_create",
        "crypto/cts.c:crypto_cts_free",
        "crypto/xts.c:create",
        "crypto/xts.c:free",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/ctr.c:crypto_rfc3686_free",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4543_free",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_rfc4106_free",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_create_common",
        "crypto/gcm.c:crypto_gcm_free",
        "crypto/gcm.c:crypto_gcm_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875952,
      "name": "crypto_drop_spawn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
