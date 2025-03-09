# Function: <code>gcm_hash_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583271385,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:224",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
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
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583480113,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:224",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598528,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:224",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598528,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786976,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:221",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786976,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583889920,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889920,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584279504,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584279504,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584398160,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398160,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432464,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432464,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584829824,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829824,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522224,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522224,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282448,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282448,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586525248,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525248,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586802231,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:202",
      "file": "crypto/gcm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495711184,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495711184,
      "name": "gcm_hash_update",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229064460,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229064460,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289859568,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289859568,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274859250,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274859250,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858656,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858656,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583795712,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583795712,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842416,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842416,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
```

```json
{
  "name": "gcm_hash_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943488,
      "name": "gcm_hash_update",
      "external": false,
      "loc": "crypto/gcm.c:208",
      "file": "crypto/gcm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/gcm.c:gcm_hash_init_continue",
        "crypto/gcm.c:gcm_hash_assoc_continue",
        "crypto/gcm.c:gcm_hash_assoc_remain_continue",
        "crypto/gcm.c:gcm_hash_crypt_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943488,
      "name": "gcm_hash_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
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
int gcm_hash_update(struct aead_request * req, crypto_completion_t compl, struct scatterlist * src, unsigned int len, u32 flags)
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
