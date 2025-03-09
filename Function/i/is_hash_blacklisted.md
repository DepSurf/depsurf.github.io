# Function: <code>is_hash_blacklisted</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636896,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:113",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636896,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719056,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:113",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719056,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854560,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:113",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854560,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923024,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:113",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923024,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019008,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019008,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074336,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074336,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259712,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259712,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301760,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301760,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319456,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:116",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319456,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564880,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:116",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564880,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918656,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:221",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918656,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354032,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:221",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354032,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557152,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:224",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557152,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727936,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:224",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727936,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492439112,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492439112,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226312636,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226312636,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285707584,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285707584,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272513750,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272513750,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043184,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043184,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990464,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990464,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034384,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034384,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```

```json
{
  "name": "is_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095952,
      "name": "is_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:109",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_binary_blacklisted",
        "crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095952,
      "name": "is_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int is_hash_blacklisted(const u8 * hash, size_t hash_len, const char * type)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum blacklist_hash_type hash_type</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * type</code>
</li>
</ul>
</details>
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
