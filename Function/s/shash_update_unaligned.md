# Function: <code>shash_update_unaligned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582660289,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:74",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582906407,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:74",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583006135,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:74",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583056487,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:75",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583222591,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:83",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583430579,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:83",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_update"
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551872,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:85",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551872,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741056,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071583743527,
      "name": "shash_update_unaligned.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850816,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850816,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239728,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:79",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239728,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358240,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:79",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358240,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392704,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:91",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392704,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787936,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:91",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787936,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585473728,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:91",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473728,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235248,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:81",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_update",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235248,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586471104,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:90",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_finup",
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471104,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495665736,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495665736,
      "name": "shash_update_unaligned",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229018808,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229018808,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289804240,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289804240,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274817024,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274817024,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819552,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819552,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756608,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756608,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803312,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803312,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
```

```json
{
  "name": "shash_update_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904352,
      "name": "shash_update_unaligned",
      "external": false,
      "loc": "crypto/shash.c:80",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904352,
      "name": "shash_update_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int shash_update_unaligned(struct shash_desc * desc, const u8 * data, unsigned int len)
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
