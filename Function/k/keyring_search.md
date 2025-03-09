# Function: <code>keyring_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193408,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:889",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193408,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409888,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:913",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409888,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502080,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:913",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502080,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583360,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:920",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583360,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736352,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:917",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736352,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935008,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:910",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935008,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043536,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:907",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043536,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225856,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225856,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331664,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331664,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665344,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665344,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786800,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786800,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810944,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810944,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173984,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173984,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773920,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "fs/crypto/keyring.c:fscrypt_find_master_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773920,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470304,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470304,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585701904,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701904,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585948944,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:937",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:find_master_key_user",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:request_asymmetric_key",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948944,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495074640,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495074640,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228470180,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228470180,
      "name": "keyring_search",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288971232,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288971232,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274341514,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274341514,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300400,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300400,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237536,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237536,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284432,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284432,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type * type, const char * description, bool recurse)
```

```json
{
  "name": "keyring_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379008,
      "name": "keyring_search",
      "external": true,
      "loc": "security/keys/keyring.c:941",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/crypto/keyring.c:search_fscrypt_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379008,
      "name": "keyring_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool recurse</code>
</li>
</ul>
</details>
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
