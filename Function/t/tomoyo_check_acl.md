# Function: <code>tomoyo_check_acl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439136,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:156",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439136,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660896,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:156",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660896,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753952,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:156",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753952,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846256,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:158",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846256,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583003104,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:159",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003104,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203760,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:159",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203760,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320672,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:159",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320672,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583508288,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:159",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508288,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614176,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614176,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971200,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971200,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584091056,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091056,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584118336,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118336,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584499664,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499664,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585136512,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585136512,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585861248,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585861248,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093200,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093200,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586342304,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586342304,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495397072,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495397072,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228769776,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228769776,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289424848,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289424848,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274597684,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274597684,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582912,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582912,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519968,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519968,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566688,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566688,
      "name": "tomoyo_check_acl",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info * r, bool (*)(struct tomoyo_request_info *, const struct tomoyo_acl_info *) check_entry)
```

```json
{
  "name": "tomoyo_check_acl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663824,
      "name": "tomoyo_check_acl",
      "external": true,
      "loc": "security/tomoyo/domain.c:161",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/environ.c:tomoyo_env_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_execute_permission",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663824,
      "name": "tomoyo_check_acl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
