# Function: <code>shash_final_unaligned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582660536,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:112",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582906670,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:112",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583006398,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:112",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583056770,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:113",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583222884,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:121",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583430871,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:121",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_final"
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552208,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:129",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552208,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741376,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071583743552,
      "name": "shash_final_unaligned.cold",
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851152,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851152,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240080,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:123",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240080,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358592,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:123",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358592,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584393056,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:135",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393056,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788288,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:135",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788288,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474144,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:135",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474144,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235696,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:125",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:shash_ahash_finup",
        "crypto/shash.c:shash_async_final",
        "crypto/shash.c:crypto_shash_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235696,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586471472,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:140",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_finup",
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471472,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495666160,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495666160,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229019140,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229019140,
      "name": "shash_final_unaligned",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289804784,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289804784,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274817340,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274817340,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819888,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819888,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756944,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756944,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803648,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803648,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
```

```json
{
  "name": "shash_final_unaligned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904688,
      "name": "shash_final_unaligned",
      "external": false,
      "loc": "crypto/shash.c:124",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/shash.c:crypto_shash_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904688,
      "name": "shash_final_unaligned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
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
int shash_final_unaligned(struct shash_desc * desc, u8 * out)
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
