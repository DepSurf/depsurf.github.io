# Function: <code>asymmetric_key_id_same</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582696176,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:68",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696176,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582973965,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974720,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583078541,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079296,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583133164,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:158",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132864,
      "name": "asymmetric_key_id_same.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583132912,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583307815,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:160",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307504,
      "name": "asymmetric_key_id_same.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583307552,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583516452,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:160",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516064,
      "name": "asymmetric_key_id_same.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583516112,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583638372,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:161",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637984,
      "name": "asymmetric_key_id_same.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583638032,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583825955,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823888,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583823936,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927923,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925856,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583925904,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584319392,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317376,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584437760,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435744,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584471840,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:158",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470416,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584869936,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:158",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868528,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585566039,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:171",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563136,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586329959,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:171",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586326688,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573264,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:170",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573264,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586841536,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:170",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp_name",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841536,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495745460,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495744416,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336495744512,
      "name": "asymmetric_key_id_same",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229098800,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/restrict.c:match_either_id",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229098020,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3229098088,
      "name": "asymmetric_key_id_same",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289909300,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289904992,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055289905104,
      "name": "asymmetric_key_id_same",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274894014,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274895472,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583896659,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894592,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583894640,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583833715,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831648,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583831696,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583880419,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878352,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583878400,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool asymmetric_key_id_same(const struct asymmetric_key_id * kid1, const struct asymmetric_key_id * kid2)
```

```json
{
  "name": "asymmetric_key_id_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583981491,
      "name": "asymmetric_key_id_same",
      "external": true,
      "loc": "crypto/asymmetric_keys/asymmetric_type.c:157",
      "file": "crypto/asymmetric_keys/asymmetric_type.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key"
      ],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_cmp",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/restrict.c:key_or_keyring_common",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/x509_public_key.c:x509_check_for_self_signed",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979424,
      "name": "asymmetric_key_id_same.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583979472,
      "name": "asymmetric_key_id_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
