# Function: <code>keyring_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191424,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:492",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_thread_keyring_to_cred",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191424,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407888,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:492",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_thread_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/ima/ima_mok.c:ima_mok_init",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407888,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500080,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:492",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_thread_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500080,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580928,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:499",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580928,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733808,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:494",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733808,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932528,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:494",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932528,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041040,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:494",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/process_keys.c:install_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041040,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222464,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222464,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328272,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328272,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583661568,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661568,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583783024,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783024,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583807216,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807216,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169760,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169760,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584769248,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:do_add_master_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769248,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585465360,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585465360,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697008,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697008,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943920,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:517",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:key_get_persistent",
        "security/keys/persistent.c:key_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "security/integrity/digsig.c:integrity_init_keyring",
        "block/sed-opal.c:sed_opal_init",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943920,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495069936,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495069936,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228466632,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228466632,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288965792,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288965792,
      "name": "keyring_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274338350,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274338350,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297008,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297008,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234144,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234144,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281040,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281040,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct key * keyring_alloc(const char * description, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link, struct key * dest)
```

```json
{
  "name": "keyring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375584,
      "name": "keyring_alloc",
      "external": true,
      "loc": "security/keys/keyring.c:521",
      "file": "security/keys/keyring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/system_keyring.c:system_trusted_keyring_init",
        "certs/blacklist.c:blacklist_init",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key",
        "fs/verity/signature.c:fsverity_init_signature",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:install_session_keyring_to_cred",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/process_keys.c:look_up_user_keyrings",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/integrity/digsig.c:integrity_init_keyring",
        "net/dns_resolver/dns_key.c:init_dns_resolver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375584,
      "name": "keyring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<b>Param added. </b>
<code>int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link</code>
</li>
<li>
<b>Param reordered. </b>
<code>description, uid, gid, cred, perm, flags, dest</code> ➡️ <code>description, uid, gid, cred, perm, flags, restrict_link, dest</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link</code> ➡️ <code>struct key_restriction * restrict_link</code>
</li>
</ul>
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
