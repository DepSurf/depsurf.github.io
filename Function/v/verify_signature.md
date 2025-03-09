# Function: <code>verify_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582696832,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:28",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696832,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975136,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:46",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975136,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079712,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:46",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079712,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135824,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:46",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135824,
      "name": "verify_signature",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583310512,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:46",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310512,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519120,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:46",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519120,
      "name": "verify_signature",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641120,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:141",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641120,
      "name": "verify_signature",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827232,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827232,
      "name": "verify_signature",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929200,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929200,
      "name": "verify_signature",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320576,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320576,
      "name": "verify_signature",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438848,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438848,
      "name": "verify_signature",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473520,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473520,
      "name": "verify_signature",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871648,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871648,
      "name": "verify_signature",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567616,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567616,
      "name": "verify_signature",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586331680,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586331680,
      "name": "verify_signature",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578336,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578336,
      "name": "verify_signature",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846928,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846928,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495748216,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495748216,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229101404,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229101404,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289911376,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289911376,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274896564,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274896564,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897936,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897936,
      "name": "verify_signature",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583834992,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834992,
      "name": "verify_signature",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881696,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881696,
      "name": "verify_signature",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int verify_signature(const struct key * key, const struct public_key_signature * sig)
```

```json
{
  "name": "verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982768,
      "name": "verify_signature",
      "external": true,
      "loc": "crypto/asymmetric_keys/signature.c:137",
      "file": "crypto/asymmetric_keys/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:restrict_link_by_signature",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust",
        "crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982768,
      "name": "verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
