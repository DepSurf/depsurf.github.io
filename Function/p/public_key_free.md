# Function: <code>public_key_free</code>

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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975296,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975296,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079872,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079872,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583136070,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136832,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583310726,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:44",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311664,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583519333,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:44",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520256,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641429,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:44",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642816,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827573,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827824,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929541,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929792,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584321109,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321168,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584439349,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439408,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584474037,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:43",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474096,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584872165,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:43",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872224,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585568613,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:43",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568688,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586333381,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:43",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586333472,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586582229,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586582320,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586850869,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:42",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850960,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495748788,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495749496,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229101796,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229102040,
      "name": "public_key_free",
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289912004,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289913024,
      "name": "public_key_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274897008,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274898486,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583898277,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898528,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583835333,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835584,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583882037,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882288,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
```

```json
{
  "name": "public_key_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583983109,
      "name": "public_key_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/public_key.c:40",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983360,
      "name": "public_key_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void public_key_free(struct public_key * key)
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
