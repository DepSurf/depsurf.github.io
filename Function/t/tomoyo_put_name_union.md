# Function: <code>tomoyo_put_name_union</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445040,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:66",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445040,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666976,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:66",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666976,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760032,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:66",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760032,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852448,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:66",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852448,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009392,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009392,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210080,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210080,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327008,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327008,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514400,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514400,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620288,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620288,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977680,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977680,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097488,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097488,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125088,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125088,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506848,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506848,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144256,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144256,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869440,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869440,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586101328,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101328,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586350624,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586350624,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495404104,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495404104,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228776196,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228776196,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289442588,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl"
      ],
      "caller_func": [
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289437424,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274607108,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl"
      ],
      "caller_func": [
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274603678,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589024,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589024,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526080,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526080,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583572800,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572800,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tomoyo_put_name_union(struct tomoyo_name_union * ptr)
```

```json
{
  "name": "tomoyo_put_name_union",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669968,
      "name": "tomoyo_put_name_union",
      "external": true,
      "loc": "security/tomoyo/file.c:67",
      "file": "security/tomoyo/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mount_acl",
        "security/tomoyo/file.c:tomoyo_update_mkdev_acl",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/network.c:tomoyo_write_unix_network"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669968,
      "name": "tomoyo_put_name_union",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
