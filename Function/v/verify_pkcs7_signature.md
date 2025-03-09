# Function: <code>verify_pkcs7_signature</code>

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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545360,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:208",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545360,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609536,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:208",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609536,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636448,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:206",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636448,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718608,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:206",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718608,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:207",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854439,
      "name": "verify_pkcs7_signature.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071580854112,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:207",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922903,
      "name": "verify_pkcs7_signature.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071580922576,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:205",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018903,
      "name": "verify_pkcs7_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581018544,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074112,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074112,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259456,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259456,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301552,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301552,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319088,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:267",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319088,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564512,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:267",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564512,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917744,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:309",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/module/signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917744,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353104,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:309",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353104,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556000,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:317",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556000,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726784,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:396",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/module/signing.c:mod_verify_sig",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726784,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492438776,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492438776,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226312404,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226312404,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285707184,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285707184,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272513392,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272513392,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042960,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042960,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990240,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990240,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034160,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034160,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
```

```json
{
  "name": "verify_pkcs7_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095728,
      "name": "verify_pkcs7_signature",
      "external": true,
      "loc": "certs/system_keyring.c:283",
      "file": "certs/system_keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module_signing.c:mod_verify_sig",
        "kernel/module_signing.c:mod_verify_sig",
        "fs/verity/signature.c:fsverity_verify_signature",
        "crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095728,
      "name": "verify_pkcs7_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int verify_pkcs7_signature(const void * data, size_t len, const void * raw_pkcs7, size_t pkcs7_len, struct key * trusted_keys, enum key_being_used_for usage, int (*)(void *, const void *, size_t, size_t) view_content, void * ctx)
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
