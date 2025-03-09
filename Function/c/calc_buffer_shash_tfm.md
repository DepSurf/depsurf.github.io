# Function: <code>calc_buffer_shash_tfm</code>

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
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582861343,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:579",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
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
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582958191,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:581",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
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
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583008315,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:581",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
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
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583173035,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:569",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
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
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583379016,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:571",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583494352,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:585",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494352,
      "name": "calc_buffer_shash_tfm",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681424,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:580",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681424,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788784,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788784,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180976,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:729",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180976,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300208,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:719",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300208,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334576,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:719",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334576,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584722896,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:719",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722896,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585398320,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:720",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398320,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151536,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:720",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151536,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389728,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:720",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389728,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654464,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:720",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654464,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495592136,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495592136,
      "name": "calc_buffer_shash_tfm",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228952844,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228952844,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289693360,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289693360,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274755946,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274755946,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757520,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757520,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694576,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694576,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741280,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741280,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "calc_buffer_shash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842224,
      "name": "calc_buffer_shash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:588",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842224,
      "name": "calc_buffer_shash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int calc_buffer_shash_tfm(const void * buf, loff_t size, struct ima_digest_data * hash, struct crypto_shash * tfm)
```
</details>
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
