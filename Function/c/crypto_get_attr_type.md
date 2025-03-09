# Function: <code>crypto_get_attr_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582634192,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:732",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/blkcipher.c:skcipher_geniv_alloc",
        "crypto/chainiv.c:chainiv_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634192,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582884101,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:731",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/ctr.c:crypto_rfc3686_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883744,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582980677,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:732",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980320,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583030501,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:732",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030112,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195797,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:744",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195392,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583404101,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:741",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404032,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524037,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:750",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523968,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712261,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:761",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711872,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821877,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821488,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584219733,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:801",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/geniv.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216592,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584338117,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:803",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334960,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584372645,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:803",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369488,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584767861,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:803",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764656,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585452789,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:827",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447824,
      "name": "crypto_get_attr_type",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586210629,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:846",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206112,
      "name": "crypto_get_attr_type",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586451733,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:858",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444400,
      "name": "crypto_get_attr_type",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586717621,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:859",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586710256,
      "name": "crypto_get_attr_type",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495629156,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495628616,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228987248,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228986816,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289755048,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289754112,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274787190,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274786458,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583790613,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790224,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583727669,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727280,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583774373,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773984,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct crypto_attr_type * crypto_get_attr_type(struct rtattr * * tb)
```

```json
{
  "name": "crypto_get_attr_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583875365,
      "name": "crypto_get_attr_type",
      "external": true,
      "loc": "crypto/algapi.c:771",
      "file": "crypto/algapi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_check_attr_type"
      ],
      "caller_func": [
        "crypto/aead.c:aead_geniv_alloc",
        "crypto/skcipher.c:skcipher_alloc_instance_simple",
        "crypto/seqiv.c:seqiv_create",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_create",
        "crypto/cts.c:crypto_cts_create",
        "crypto/xts.c:create",
        "crypto/ctr.c:crypto_rfc3686_create",
        "crypto/gcm.c:crypto_rfc4543_create",
        "crypto/gcm.c:crypto_rfc4106_create",
        "crypto/gcm.c:crypto_gcm_create_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874976,
      "name": "crypto_get_attr_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
