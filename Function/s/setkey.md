# Function: <code>setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582633504,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:46",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582646960,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:329",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582649264,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:397",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583055483,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633504,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071582646960,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071582649264,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883056,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:46",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582894528,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:326",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582897200,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:397",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071582941360,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:33",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583349616,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883056,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071582894528,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582897200,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582941360,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582979664,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:46",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582991008,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:326",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993664,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:397",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583044304,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:58",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583474992,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979664,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071582991008,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582993664,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071583044304,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583029456,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:46",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583041024,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:327",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583043632,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:398",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583098240,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:58",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583497214,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029456,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071583041024,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071583043632,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071583098240,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194704,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:46",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583206384,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:327",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583209008,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:398",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583264832,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:58",
      "file": "crypto/xts.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583679246,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194704,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583206384,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583209008,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583264832,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583403360,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:47",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583414816,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:322",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583417328,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:395",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583472240,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:58",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583897045,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:160",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403360,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583414816,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583417328,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583472240,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583523408,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:47",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583535520,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:322",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583537968,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:395",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583594816,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:44",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583981317,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:160",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523408,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583535520,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583537968,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071583594816,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711168,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583725536,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583728320,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583782480,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584163906,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711168,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583725536,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583728320,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583782480,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583820784,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583835232,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583838000,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583885392,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584297602,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820784,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583835232,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583838000,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583885392,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_skcipher * parent, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584275296,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584708109,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275296,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584821293,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584865965,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585288760,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586142468,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587135348,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587397490,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
  "name": "setkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587731842,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495627528,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495645784,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495648560,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446603336495704640,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496183960,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495627528,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446603336495645784,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446603336495648560,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446603336495704640,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228985948,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229002320,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229005008,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 3229058608,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229504472,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:find_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228985948,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 3229002320,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 3229005008,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 3229058608,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289753264,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289780848,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289784672,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 13835058055289852848,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290460492,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289753264,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 13835058055289780848,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 13835058055289784672,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 13835058055289852848,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274785424,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274799928,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274802332,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446743936274852938,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275236608,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274852938,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446743936274785424,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446743936274799928,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446743936274802332,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583789520,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583803968,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583806736,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583854128,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584266338,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789520,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583803968,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583806736,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583854128,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583726576,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583741024,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583743792,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583791184,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584201538,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726576,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583741024,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583743792,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583791184,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583773280,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583787728,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583790496,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583837888,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584250098,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773280,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583787728,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583790496,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583837888,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int setkey(struct crypto_tfm * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "setkey",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583874272,
      "name": "setkey",
      "external": false,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583888736,
      "name": "setkey",
      "external": false,
      "loc": "crypto/ablkcipher.c:317",
      "file": "crypto/ablkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583891584,
      "name": "setkey",
      "external": false,
      "loc": "crypto/blkcipher.c:390",
      "file": "crypto/blkcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/blkcipher.c:async_setkey"
      ]
    },
    {
      "addr": 18446744071583938960,
      "name": "setkey",
      "external": false,
      "loc": "crypto/xts.c:40",
      "file": "crypto/xts.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584355026,
      "name": "setkey",
      "external": false,
      "loc": "lib/btree.c:158",
      "file": "lib/btree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874272,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071583888736,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583891584,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071583938960,
      "name": "setkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_skcipher * parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm * tfm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int setkey(struct crypto_skcipher * parent, const u8 * key, unsigned int keylen)
```
</details>
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
