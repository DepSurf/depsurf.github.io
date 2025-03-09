# Function: <code>ecryptfs_dump_hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036112,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036112,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249712,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249712,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339184,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339184,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582424672,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424112,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071582424880,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575139,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574576,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071582575344,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767925,
      "name": "ecryptfs_dump_hex.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071582767280,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:98",
      "file": "fs/ecryptfs/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871925,
      "name": "ecryptfs_dump_hex.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071582871280,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583046250,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045808,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583046464,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583152474,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152032,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583152688,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583474707,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474992,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583583875,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583584160,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583607091,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607376,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965491,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965776,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547721,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548000,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585223305,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223600,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585452825,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453120,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585687625,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_1_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687920,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494861860,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494861288,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446603336494861952,
      "name": "ecryptfs_dump_hex",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228279868,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228279352,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3228280080,
      "name": "ecryptfs_dump_hex",
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288717228,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288716480,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 13835058055288717360,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274183324,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274182802,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446743936274183676,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583121210,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120768,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583121424,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583058362,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057920,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583058576,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583109818,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109376,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583110032,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ecryptfs_dump_hex(char * data, int bytes)
```

```json
{
  "name": "ecryptfs_dump_hex",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583199018,
      "name": "ecryptfs_dump_hex",
      "external": true,
      "loc": "fs/ecryptfs/debug.c:84",
      "file": "fs/ecryptfs/debug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/crypto.c:ecryptfs_derive_iv",
        "fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198576,
      "name": "ecryptfs_dump_hex.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583199232,
      "name": "ecryptfs_dump_hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
