# Function: <code>key_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187120,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187120,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403504,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403504,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, int (*)(struct key *, const struct key_type *, const union key_payload *) restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495696,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495696,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576576,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:228",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576576,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1023
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582729376,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:228",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729376,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1046
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927888,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:228",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927888,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036448,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:228",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036448,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1093
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218480,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218480,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324288,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324288,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583656928,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656928,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1199
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778384,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778384,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1216
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802384,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802384,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164928,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164928,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763984,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763984,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1378
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585459776,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459776,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1378
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691296,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691296,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1387
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585938352,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:225",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_alloc_key",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938352,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1401
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495065424,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495065424,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1416
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228462492,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228462492,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288959360,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288959360,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1772
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274334268,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274334268,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583293024,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293024,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230160,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230160,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583277056,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277056,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
struct key * key_alloc(struct key_type * type, const char * desc, kuid_t uid, kgid_t gid, const struct cred * cred, key_perm_t perm, long unsigned int flags, struct key_restriction * restrict_link)
```

```json
{
  "name": "key_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371552,
      "name": "key_alloc",
      "external": true,
      "loc": "security/keys/key.c:224",
      "file": "security/keys/key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keyring.c:add_master_key_user",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_alloc",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371552,
      "name": "key_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1162
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
