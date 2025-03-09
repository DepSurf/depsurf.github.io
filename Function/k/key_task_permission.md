# Function: <code>key_task_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201648,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201648,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582418368,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418368,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582510544,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510544,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592304,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592304,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745488,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745488,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945536,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945536,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583054640,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:30",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_aux",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054640,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238048,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238048,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343872,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343872,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678480,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678480,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799984,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799984,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824176,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824176,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187216,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187216,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788064,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788064,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485328,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485328,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585716800,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716800,
      "name": "key_task_permission",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, enum key_need_perm need_perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585963920,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/key.c:__key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_get_dest_keyring",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:key_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963920,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495087952,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495087952,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228481620,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228481620,
      "name": "key_task_permission",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288987952,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288987952,
      "name": "key_task_permission",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274351032,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274351032,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312608,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312608,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249712,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249712,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296640,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296640,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int key_task_permission(const key_ref_t key_ref, const struct cred * cred, unsigned int perm)
```

```json
{
  "name": "key_task_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391280,
      "name": "key_task_permission",
      "external": true,
      "loc": "security/keys/permission.c:26",
      "file": "security/keys/permission.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/key.c:key_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/key.c:key_create_or_update",
        "security/keys/keyring.c:find_keyring_by_name",
        "security/keys/keyring.c:keyring_search_rcu",
        "security/keys/keyring.c:search_nested_keyrings",
        "security/keys/keyring.c:keyring_search_iterator",
        "security/keys/keyctl.c:keyctl_read_key",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/request_key.c:request_key_and_link",
        "security/keys/request_key.c:construct_key_and_link",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/persistent.c:keyctl_get_persistent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391280,
      "name": "key_task_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
<code>unsigned int perm</code>
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
