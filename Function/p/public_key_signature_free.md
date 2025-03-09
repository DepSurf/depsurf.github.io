# Function: <code>public_key_signature_free</code>

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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975216,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:25",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975216,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079792,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:25",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079792,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135904,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:25",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135904,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583310592,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:25",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310592,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583519200,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:25",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519200,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641296,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:27",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641296,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827408,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827408,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929376,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929376,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584320752,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320752,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584439024,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439024,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584473696,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473696,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584871824,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871824,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585567808,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567808,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586331936,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586331936,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586578592,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578592,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586847184,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847184,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495748560,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495748560,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229101616,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229101616,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289911712,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289911712,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274896834,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274896834,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583898112,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898112,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583835168,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835168,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881872,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881872,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
```

```json
{
  "name": "public_key_signature_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583982944,
      "name": "public_key_signature_free",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:23",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982944,
      "name": "public_key_signature_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void public_key_signature_free(struct public_key_signature * sig)
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
