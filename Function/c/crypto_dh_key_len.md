# Function: <code>crypto_dh_key_len</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060562,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:36",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "crypto/dh_helper.c:crypto_dh_encode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060480,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583226654,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:36",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "crypto/dh_helper.c:crypto_dh_encode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226576,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583434665,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:36",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "crypto/dh_helper.c:crypto_dh_encode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434576,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583556348,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:38",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583556240,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745544,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745424,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855288,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855168,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584245160,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245040,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584363848,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363728,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398248,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398128,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584793480,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793360,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585482625,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:__crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh.c:dh_safe_prime_set_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482176,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586244564,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:__crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh.c:dh_safe_prime_set_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244016,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586484537,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:__crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh.c:dh_safe_prime_set_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483968,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586754521,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:__crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh.c:dh_safe_prime_set_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586753952,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495671816,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495671640,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229023748,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229023572,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289811844,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289811680,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274822576,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274821862,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583824024,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823904,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583761080,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760960,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583807784,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807664,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned int crypto_dh_key_len(const struct dh * p)
```

```json
{
  "name": "crypto_dh_key_len",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583908856,
      "name": "crypto_dh_key_len",
      "external": true,
      "loc": "crypto/dh_helper.c:34",
      "file": "crypto/dh_helper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908736,
      "name": "crypto_dh_key_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int crypto_dh_key_len(const struct dh * p)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
