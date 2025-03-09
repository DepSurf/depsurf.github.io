# Function: <code>mark_hash_blacklisted</code>

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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637200,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:87",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637200,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719360,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:87",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719360,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:87",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854950,
      "name": "mark_hash_blacklisted.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580854880,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:87",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923414,
      "name": "mark_hash_blacklisted.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580923344,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019398,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581019328,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074774,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581074704,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260150,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581260080,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324034,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581302128,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:90",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266022,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581319808,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:90",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189245,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581565232,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:201",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary",
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964336,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581918832,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int mark_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354240,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:201",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary",
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354240,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int mark_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557360,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:204",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary",
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557360,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int mark_hash_blacklisted(const u8 * hash, size_t hash_len, enum blacklist_hash_type hash_type)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582728144,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:204",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary",
        "security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728144,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492439584,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492439584,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226313040,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226313040,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285708176,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285708176,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272514162,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272514162,
      "name": "mark_hash_blacklisted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043622,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581043552,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990902,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580990832,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034822,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581034752,
      "name": "mark_hash_blacklisted",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int mark_hash_blacklisted(const char * hash)
```

```json
{
  "name": "mark_hash_blacklisted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_hash_blacklisted",
      "external": true,
      "loc": "certs/blacklist.c:83",
      "file": "certs/blacklist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096390,
      "name": "mark_hash_blacklisted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581096320,
      "name": "mark_hash_blacklisted",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int mark_hash_blacklisted(const char * hash)
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
<code>size_t hash_len</code>
</li>
<li>
<b>Param added. </b>
<code>enum blacklist_hash_type hash_type</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char * hash</code> ➡️ <code>const u8 * hash</code>
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
