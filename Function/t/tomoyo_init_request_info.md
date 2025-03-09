# Function: <code>tomoyo_init_request_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468000,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1002",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468000,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582690208,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1002",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690208,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582783264,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1002",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582783264,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875824,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1004",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875824,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583032576,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:984",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032576,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233024,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:984",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233024,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350304,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:984",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350304,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538048,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:996",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538048,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643776,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643776,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001152,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001152,
      "name": "tomoyo_init_request_info",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120960,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120960,
      "name": "tomoyo_init_request_info",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584148480,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148480,
      "name": "tomoyo_init_request_info",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532496,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532496,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585172464,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172464,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899744,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899744,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131568,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131568,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380848,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:1019",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380848,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495434912,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495434912,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228803172,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228803172,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289476960,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289476960,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274627502,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274627502,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612512,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612512,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549568,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549568,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596288,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596288,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int tomoyo_init_request_info(struct tomoyo_request_info * r, struct tomoyo_domain_info * domain, const u8 index)
```

```json
{
  "name": "tomoyo_init_request_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583693376,
      "name": "tomoyo_init_request_info",
      "external": true,
      "loc": "security/tomoyo/util.c:997",
      "file": "security/tomoyo/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_permission",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693376,
      "name": "tomoyo_init_request_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
