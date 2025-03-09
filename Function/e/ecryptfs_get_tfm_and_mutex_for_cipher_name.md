# Function: <code>ecryptfs_get_tfm_and_mutex_for_cipher_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_blkcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019440,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1750",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019440,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232976,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1741",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232976,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582322464,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1741",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322464,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407248,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1741",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407248,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557968,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1718",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557968,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1718",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751947,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582749680,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1718",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855802,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582853472,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1712",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030647,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583028224,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136867,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583134432,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1699",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457751,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583455584,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1699",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591356814,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583568384,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1693",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591299684,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583591328,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1693",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592284673,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583949616,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1693",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594066891,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584531328,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585203648,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1693",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203648,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432640,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1669",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432640,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667312,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1669",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667312,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494845424,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494845424,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228264084,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228264084,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288696480,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288696480,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274167428,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274167428,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105603,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583103168,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042755,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583040320,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094211,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583091776,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int ecryptfs_get_tfm_and_mutex_for_cipher_name(struct crypto_skcipher * * tfm, struct mutex * * tfm_mutex, char * cipher_name)
```

```json
{
  "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:1714",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583183420,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583180992,
      "name": "ecryptfs_get_tfm_and_mutex_for_cipher_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<b>Param type changed. </b>
<code>struct crypto_blkcipher * * tfm</code> ➡️ <code>struct crypto_skcipher * * tfm</code>
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
