# Function: <code>key_payload_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184416,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:362",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184416,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400736,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:367",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400736,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492928,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:367",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492928,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573808,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:368",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573808,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726560,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:370",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726560,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927168,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:370",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927168,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035728,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:371",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035728,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217744,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217744,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323552,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323552,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583656128,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:370",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_end",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656128,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777584,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_end",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777584,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583801696,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_end",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583801696,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164240,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_end",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164240,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760128,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760128,
      "name": "key_payload_reserve",
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585455664,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455664,
      "name": "key_payload_reserve",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687024,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:372",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687024,
      "name": "key_payload_reserve",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585933920,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:373",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585933920,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495063880,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495063880,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228459260,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228459260,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288953904,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_end",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288953904,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274333276,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274333276,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292288,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292288,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229424,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229424,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276320,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276320,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int key_payload_reserve(struct key * key, size_t datalen)
```

```json
{
  "name": "key_payload_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368544,
      "name": "key_payload_reserve",
      "external": true,
      "loc": "security/keys/key.c:369",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_user_key_instantiate",
        "security/keys/keyring.c:keyring_revoke",
        "security/keys/keyring.c:keyring_clear",
        "security/keys/keyring.c:key_move",
        "security/keys/keyring.c:key_unlink",
        "security/keys/keyring.c:__key_link_begin",
        "security/keys/user_defined.c:user_revoke",
        "security/keys/user_defined.c:user_update",
        "security/keys/big_key.c:big_key_revoke",
        "security/keys/trusted.c:trusted_payload_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368544,
      "name": "key_payload_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
