# Function: <code>verify_pkcs7_message_sig</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074226,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581073840,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259570,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581259200,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324012,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581301296,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:182",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265901,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581318800,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:182",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189124,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581564224,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:224",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964289,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581917424,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352736,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:224",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352736,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555632,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:232",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555632,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726432,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:311",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726432,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492438472,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492438472,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226312060,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226312060,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285706752,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285706752,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272513154,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272513154,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043074,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581042688,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990354,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580989968,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034274,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581033888,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_message_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_message_sig",
      "external": true,
      "loc": "certs/system_keyring.c:204",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:verify_pkcs7_signature",
        "security/integrity/ima/ima_modsig.c:ima_modsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095842,
      "name": "verify_pkcs7_message_sig.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581095456,
      "name": "verify_pkcs7_message_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int verify_pkcs7_message_sig(const void * data, size_t len, struct pkcs7_message * pkcs7, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```
</details>
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
