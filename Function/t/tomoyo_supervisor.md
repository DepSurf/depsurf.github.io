# Function: <code>tomoyo_supervisor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582427840,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1995",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427840,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648976,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1995",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648976,
      "name": "tomoyo_supervisor",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742048,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1995",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742048,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1675
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834480,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1995",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834480,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1598
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991312,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1996",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991312,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1599
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191872,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1996",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191872,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1589
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308208,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:1997",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308208,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1639
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583495552,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2057",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495552,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1577
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601584,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601584,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1535
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583959600,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959600,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079456,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079456,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107040,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107040,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592303179,
      "name": "tomoyo_supervisor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584487568,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1198
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2050",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594084438,
      "name": "tomoyo_supervisor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585122496,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1253
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2050",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596098533,
      "name": "tomoyo_supervisor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585846880,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1229
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2050",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596621678,
      "name": "tomoyo_supervisor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586078848,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2051",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597527987,
      "name": "tomoyo_supervisor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586327856,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495383904,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495383904,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1748
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228757384,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228757384,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289403648,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289403648,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2080
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274586894,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274586894,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570320,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570320,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1535
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583507376,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507376,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1535
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583554096,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554096,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1535
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
int tomoyo_supervisor(struct tomoyo_request_info * r, const char * fmt, void (anon))
```

```json
{
  "name": "tomoyo_supervisor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583651152,
      "name": "tomoyo_supervisor",
      "external": true,
      "loc": "security/tomoyo/common.c:2059",
      "file": "security/tomoyo/common.c",
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
        "security/tomoyo/network.c:tomoyo_audit_inet_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651152,
      "name": "tomoyo_supervisor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1520
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
