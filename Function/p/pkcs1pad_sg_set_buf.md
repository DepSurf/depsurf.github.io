# Function: <code>pkcs1pad_sg_set_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912176,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:170",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912176,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583015284,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:170",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014000,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583066500,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:164",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065264,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583232708,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:164",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231472,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583440724,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:164",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439440,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583563044,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:164",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561888,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751968,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750304,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583861709,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860048,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584248477,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250640,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584367142,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369280,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584401558,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403744,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584796790,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798976,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585485971,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488384,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586248387,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250688,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586490163,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:162",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490704,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586759411,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:185",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760736,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495677024,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495677024,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229030240,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229028800,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289817440,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289817440,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274824746,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274824746,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583830445,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828784,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767501,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765840,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583814205,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812544,
      "name": "pkcs1pad_sg_set_buf",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
```

```json
{
  "name": "pkcs1pad_sg_set_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583915277,
      "name": "pkcs1pad_sg_set_buf",
      "external": false,
      "loc": "crypto/rsa-pkcs1pad.c:161",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt"
      ],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_sign",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913616,
      "name": "pkcs1pad_sg_set_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void pkcs1pad_sg_set_buf(struct scatterlist * sg, void * buf, size_t len, struct scatterlist * next)
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
