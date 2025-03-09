# Function: <code>pkcs7_validate_trust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring, bool * _trusted)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705856,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:172",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_verify_data",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705856,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983616,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:161",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983616,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583088176,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:161",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583088176,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144480,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:161",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144480,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319376,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:161",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319376,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528144,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:162",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528144,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583651488,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:162",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651488,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583838464,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838464,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940400,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940400,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332192,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332192,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450144,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450144,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584485264,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485264,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584883632,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584883632,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585581296,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581296,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586347152,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586347152,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593920,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593920,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863264,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig",
        "certs/blacklist.c:is_key_on_revocation_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863264,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495760576,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495760576,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229112752,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229112752,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289928544,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289928544,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274907384,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274907384,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909136,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909136,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846192,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846192,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892896,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892896,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int pkcs7_validate_trust(struct pkcs7_message * pkcs7, struct key * trust_keyring)
```

```json
{
  "name": "pkcs7_validate_trust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993968,
      "name": "pkcs7_validate_trust",
      "external": true,
      "loc": "crypto/asymmetric_keys/pkcs7_trust.c:158",
      "file": "crypto/asymmetric_keys/pkcs7_trust.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_message_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993968,
      "name": "pkcs7_validate_trust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool * _trusted</code>
</li>
</ul>
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
