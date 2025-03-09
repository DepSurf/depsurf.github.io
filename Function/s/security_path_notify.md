# Function: <code>security_path_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394528,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394528,
      "name": "security_path_notify",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734000,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1133",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734000,
      "name": "security_path_notify",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854320,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1135",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854320,
      "name": "security_path_notify",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879344,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1180",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879344,
      "name": "security_path_notify",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244272,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1180",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244272,
      "name": "security_path_notify",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851568,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1184",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851568,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554464,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1182",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554464,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585785360,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1611",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785360,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033504,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:1664",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033504,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495146144,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495146144,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228533832,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228533832,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289067456,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289067456,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274394594,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274394594,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363264,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363264,
      "name": "security_path_notify",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300368,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300368,
      "name": "security_path_notify",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347040,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347040,
      "name": "security_path_notify",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```

```json
{
  "name": "security_path_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442224,
      "name": "security_path_notify",
      "external": true,
      "loc": "security/security.c:985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442224,
      "name": "security_path_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int security_path_notify(const struct path * path, u64 mask, unsigned int obj_type)
```
</details>
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
