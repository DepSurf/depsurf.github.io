# Function: <code>ima_calc_file_hash_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582613997,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:353",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582859418,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:353",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582956266,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:353",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583006227,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:353",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583170263,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583376600,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:333",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583495488,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:326",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495488,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682240,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:323",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682240,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583789600,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789600,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181200,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:455",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181200,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300432,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:455",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300432,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334784,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:455",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334784,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584723104,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:455",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584723104,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585398560,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:456",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585398560,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151792,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:456",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151792,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389984,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:456",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389984,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655232,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:456",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655232,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495592600,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495592600,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228953732,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228953732,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289695152,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289695152,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274756966,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274756966,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583758336,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758336,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695392,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695392,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742096,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742096,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
```

```json
{
  "name": "ima_calc_file_hash_tfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843040,
      "name": "ima_calc_file_hash_tfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:331",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843040,
      "name": "ima_calc_file_hash_tfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int ima_calc_file_hash_tfm(struct file * file, struct ima_digest_data * hash, struct crypto_shash * tfm)
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
