# Function: <code>key_create_or_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188464,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:773",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "security/keys/keyctl.c:SyS_add_key",
        "security/integrity/digsig.c:integrity_load_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188464,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582404864,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:792",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "security/keys/keyctl.c:SyS_add_key",
        "security/integrity/digsig.c:integrity_load_x509",
        "crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404864,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497056,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:792",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "security/keys/keyctl.c:SyS_add_key",
        "security/integrity/digsig.c:integrity_load_x509",
        "crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497056,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577856,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:794",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:add_trusted_secondary_key",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:SyS_add_key",
        "security/integrity/digsig.c:integrity_load_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577856,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582730736,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:800",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:add_trusted_secondary_key",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:SyS_add_key",
        "security/integrity/digsig.c:integrity_load_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730736,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1185
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929360,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:800",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:add_trusted_secondary_key",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_load_x509"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929360,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1206
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583037856,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:801",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/system_keyring.c:add_trusted_secondary_key",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037856,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1206
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219888,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219888,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325696,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325696,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658128,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:813",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658128,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779600,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:816",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779600,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1465
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803744,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:816",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/common.c:load_certificate_list",
        "certs/blacklist.c:add_key_to_revocation_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803744,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1462
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166288,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:816",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/common.c:load_certificate_list",
        "certs/blacklist.c:add_key_to_revocation_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166288,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1462
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765376,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:816",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:add_key_to_revocation_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key",
        "crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765376,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1551
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585461184,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:816",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:blacklist_init",
        "certs/blacklist.c:add_key_to_revocation_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key",
        "crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461184,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1551
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585694272,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:1003",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/blacklist.c:add_key_to_revocation_list",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key",
        "crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694272,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585941344,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:999",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:add_to_secondary_keyring",
        "certs/blacklist.c:add_key_to_revocation_list",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key",
        "crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list",
        "block/sed-opal.c:sed_opal_init",
        "block/sed-opal.c:sed_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585941344,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495067248,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__arm64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495067248,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228463952,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228463952,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288962160,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288962160,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274335960,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274335960,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294432,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294432,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231568,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231568,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278464,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278464,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
key_ref_t key_create_or_update(key_ref_t keyring_ref, const char * type, const char * description, const void * payload, size_t plen, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_create_or_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372992,
      "name": "key_create_or_update",
      "external": true,
      "loc": "security/keys/key.c:808",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:load_system_certificate_list",
        "certs/blacklist.c:mark_hash_blacklisted",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/integrity/digsig.c:integrity_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372992,
      "name": "key_create_or_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
