# Function: <code>tomoyo_fill_path_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467376,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:661",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467376,
      "name": "tomoyo_fill_path_info",
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689584,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:661",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689584,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782640,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:661",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782640,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875184,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:663",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875184,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031936,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:643",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031936,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232384,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:643",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232384,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349664,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:643",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349664,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537392,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:654",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537392,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643120,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643120,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000432,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000432,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120240,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120240,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147760,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147760,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531584,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531584,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171456,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171456,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898656,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898656,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130496,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130496,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379776,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:677",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/condition.c:tomoyo_scan_bprm",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379776,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495433984,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495433984,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228802348,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228802348,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289475056,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289475056,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274626840,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274626840,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583611856,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611856,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583548912,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548912,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583595632,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595632,
      "name": "tomoyo_fill_path_info",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info * ptr)
```

```json
{
  "name": "tomoyo_fill_path_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692720,
      "name": "tomoyo_fill_path_info",
      "external": true,
      "loc": "security/tomoyo/util.c:655",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_domain",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/util.c:tomoyo_find_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692720,
      "name": "tomoyo_fill_path_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
