# Function: <code>ima_alloc_atfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614192,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:171",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858368,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:171",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858368,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955200,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:171",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955200,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005168,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:171",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005168,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169296,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:166",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169296,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:168",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375600,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071583379948,
      "name": "ima_alloc_atfm.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:168",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494672,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071583499132,
      "name": "ima_alloc_atfm.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681648,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583685936,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789008,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583793520,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:289",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180128,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071584185609,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:289",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299296,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071591369741,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:289",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333696,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071591312444,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721904,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:289",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721904,
      "name": "ima_alloc_atfm",
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585397200,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:290",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397200,
      "name": "ima_alloc_atfm",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586150320,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:290",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150320,
      "name": "ima_alloc_atfm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586388528,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:290",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388528,
      "name": "ima_alloc_atfm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653264,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:290",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653264,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495592384,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495592384,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228953120,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228953120,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289693744,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289693744,
      "name": "ima_alloc_atfm",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274756106,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274756106,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757744,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583762256,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694800,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583699312,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741504,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583746016,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```

```json
{
  "name": "ima_alloc_atfm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_alloc_atfm",
      "external": false,
      "loc": "security/integrity/ima/ima_crypto.c:165",
      "file": "security/integrity/ima/ima_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842448,
      "name": "ima_alloc_atfm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583846960,
      "name": "ima_alloc_atfm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct crypto_ahash * ima_alloc_atfm(enum hash_algo algo)
```
</details>
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
