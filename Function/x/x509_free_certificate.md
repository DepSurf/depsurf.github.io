# Function: <code>x509_free_certificate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697936,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:48",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697936,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582976144,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976144,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583080720,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080720,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583138967,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137664,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583137744,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583313799,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312496,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583312576,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522378,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521120,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583521200,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583644906,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:47",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644448,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583644528,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583831578,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830992,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583831088,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933514,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932928,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583933024,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325682,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324304,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584324400,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443938,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442560,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584442656,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584478626,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477248,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584477344,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584876850,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875472,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584875568,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585573782,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:44",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572352,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585572448,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586338326,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:44",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336848,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586336960,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586584806,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:44",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583296,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586583408,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586853682,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:44",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851936,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586852048,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495752960,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495752400,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336495752496,
      "name": "x509_free_certificate",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229105416,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229104880,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3229104964,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289918152,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289917472,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 13835058055289917616,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274900508,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274899974,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446743936274900076,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902250,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901664,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583901760,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583839306,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838720,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583838816,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886010,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885424,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583885520,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x509_free_certificate(struct x509_certificate * cert)
```

```json
{
  "name": "x509_free_certificate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987082,
      "name": "x509_free_certificate",
      "external": true,
      "loc": "crypto/asymmetric_keys/x509_cert_parser.c:46",
      "file": "crypto/asymmetric_keys/x509_cert_parser.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986496,
      "name": "x509_free_certificate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583986592,
      "name": "x509_free_certificate",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
