# Function: <code>tomoyo_update_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438784,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:88",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/network.c:tomoyo_write_inet_network",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438784,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660560,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:88",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660560,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753616,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:88",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753616,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845888,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:90",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845888,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002720,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:91",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002720,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203360,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:91",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203360,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320272,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:91",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320272,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583507904,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:91",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507904,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613792,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613792,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970816,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_env",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970816,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090672,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_env",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090672,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584117952,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117952,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592304123,
      "name": "tomoyo_update_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584499248,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085336,
      "name": "tomoyo_update_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585136128,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596099328,
      "name": "tomoyo_update_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585860848,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596622426,
      "name": "tomoyo_update_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586092800,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597528735,
      "name": "tomoyo_update_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586341904,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495396568,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495396568,
      "name": "tomoyo_update_domain",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228769320,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228769320,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289424192,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289424192,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274597118,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274597118,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582528,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582528,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519584,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519584,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566304,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566304,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int tomoyo_update_domain(struct tomoyo_acl_info * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *) check_duplicate, bool (*)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool) merge_duplicate)
```

```json
{
  "name": "tomoyo_update_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663440,
      "name": "tomoyo_update_domain",
      "external": true,
      "loc": "security/tomoyo/domain.c:92",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network",
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663440,
      "name": "tomoyo_update_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
