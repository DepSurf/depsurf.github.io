# Function: <code>lookup_user_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203808,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:516",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203808,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1238
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420640,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:520",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:mpi_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420640,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1389
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512816,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:520",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:mpi_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512816,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1389
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582594496,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:531",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594496,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1245
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747712,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:533",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:SyS_request_key",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747712,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947792,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:533",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947792,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056896,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:533",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056896,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240720,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240720,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346544,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346544,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681376,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681376,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1694
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802880,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802880,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1700
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827072,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827072,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1780
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584190112,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190112,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1780
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584791200,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:get_instantiation_keyring",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/nvdimm/security.c:nvdimm_get_user_key_payload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584791200,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1733
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488672,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_lookup_user_key",
        "fs/crypto/keyring.c:get_keyring_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:get_instantiation_keyring",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/nvdimm/security.c:nvdimm_get_user_key_payload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488672,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1733
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720144,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_lookup_user_key",
        "fs/crypto/keyring.c:get_keyring_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:get_instantiation_keyring",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/nvdimm/security.c:nvdimm_get_user_key_payload",
        "net/handshake/tlshd.c:tls_handshake_accept",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720144,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1752
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585967264,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_lookup_user_key",
        "fs/crypto/keyring.c:get_keyring_key",
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/keyctl.c:keyctl_watch_key",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:get_instantiation_keyring",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get",
        "drivers/nvdimm/security.c:nvdimm_get_user_key_payload",
        "net/handshake/tlshd.c:tls_handshake_accept",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585967264,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1758
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495090856,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__arm64_sys_request_key",
        "security/keys/keyctl.c:__arm64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495090856,
      "name": "lookup_user_key",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228484416,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228484416,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288991888,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288991888,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1656
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274353450,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__se_sys_request_key",
        "security/keys/keyctl.c:__se_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274353450,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1030
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315280,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315280,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252384,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252384,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299312,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299312,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm)
```

```json
{
  "name": "lookup_user_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393936,
      "name": "lookup_user_key",
      "external": true,
      "loc": "security/keys/process_keys.c:611",
      "file": "security/keys/process_keys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_get_security",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_set_timeout",
        "security/keys/keyctl.c:keyctl_setperm_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_describe_key",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_move",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_unlink",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_link",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_keyring_clear",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_invalidate_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_revoke_key",
        "security/keys/keyctl.c:keyctl_update_key",
        "security/keys/keyctl.c:keyctl_get_keyring_ID",
        "security/keys/keyctl.c:__ia32_sys_request_key",
        "security/keys/keyctl.c:__x64_sys_request_key",
        "security/keys/keyctl.c:__ia32_sys_add_key",
        "security/keys/keyctl.c:__x64_sys_add_key",
        "security/keys/persistent.c:keyctl_get_persistent",
        "security/keys/dh.c:dh_data_from_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393936,
      "name": "lookup_user_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum key_need_perm need_perm</code>
</li>
<li>
<b>Param removed. </b>
<code>key_perm_t perm</code>
</li>
</ul>
</details>
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
