# Function: <code>tomoyo_realpath_from_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460528,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:250",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460528,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682768,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:250",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682768,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775824,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:250",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775824,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582868208,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:250",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868208,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025168,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:251",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025168,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225664,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:251",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225664,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342736,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:251",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342736,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530240,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:260",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530240,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636128,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636128,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993488,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993488,
      "name": "tomoyo_realpath_from_path",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113104,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113104,
      "name": "tomoyo_realpath_from_path",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140560,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140560,
      "name": "tomoyo_realpath_from_path",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524352,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524352,
      "name": "tomoyo_realpath_from_path",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163264,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163264,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585889472,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889472,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586121360,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586121360,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586370656,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:237",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370656,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495424008,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495424008,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228793592,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228793592,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289462512,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289462512,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274619316,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274619316,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604864,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604864,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541920,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541920,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583588640,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588640,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
char * tomoyo_realpath_from_path(const struct path * path)
```

```json
{
  "name": "tomoyo_realpath_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685728,
      "name": "tomoyo_realpath_from_path",
      "external": true,
      "loc": "security/tomoyo/realpath.c:235",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685728,
      "name": "tomoyo_realpath_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
