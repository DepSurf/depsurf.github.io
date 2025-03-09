# Function: <code>find_and_lock_process_key</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:74",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972320,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071581974491,
      "name": "find_and_lock_process_key.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:80",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059376,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071582062587,
      "name": "find_and_lock_process_key.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keyinfo.c:79",
      "file": "fs/crypto/keyinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582220464,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582223599,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310752,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582312483,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597184,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582599038,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668032,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071591342071,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696928,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071591284816,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022928,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071592240937,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494992,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071594019718,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090768,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090768,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317728,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317728,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535152,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535152,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493888520,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493888520,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227369164,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227369164,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287524320,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287524320,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273448986,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273448986,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279488,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582281219,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217248,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582218979,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269968,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582271699,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```

```json
{
  "name": "find_and_lock_process_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_and_lock_process_key",
      "external": false,
      "loc": "fs/crypto/keysetup_v1.c:92",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348528,
      "name": "find_and_lock_process_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071582350259,
      "name": "find_and_lock_process_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct key * find_and_lock_process_key(const char * prefix, const u8 * descriptor, unsigned int min_keysize, const struct fscrypt_key * * payload_ret)
```
</details>
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
