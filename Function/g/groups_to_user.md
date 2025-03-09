# Function: <code>groups_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579518585,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:64",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_getgroups"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579532665,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:64",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_getgroups"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557269,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:40",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_getgroups"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543749,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:41",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586934136,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1081",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579571621,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587427178,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1085",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599616,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071587731385,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1096",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599616,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579636704,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071587865596,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1081",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636704,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661520,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071588170227,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1201",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661520,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579698592,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071588375514,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698592,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579739178,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589232209,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1290",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579720586,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589230872,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1280",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579727946,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124301,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1296",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579807994,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842630,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1405",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579918294,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374190,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1527",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580072934,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593132752,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1580",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580125766,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593587379,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1596",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580169750,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:37",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594360069,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1577",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490880224,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__arm64_sys_getgroups"
      ]
    },
    {
      "addr": 18446603336501866008,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490880224,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446603336501866008,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224896972,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 3234649600,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283713288,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295293892,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271532398,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_getgroups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278204756,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674912,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071587982298,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674912,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603248,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071587695402,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603248,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672144,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071588314074,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672144,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```

```json
{
  "name": "groups_to_user",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579706272,
      "name": "groups_to_user",
      "external": false,
      "loc": "kernel/groups.c:42",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_getgroups",
        "kernel/groups.c:__x64_sys_getgroups"
      ]
    },
    {
      "addr": 18446744071588449291,
      "name": "groups_to_user",
      "external": false,
      "loc": "net/core/sock.c:1203",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706272,
      "name": "groups_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int groups_to_user(gid_t * grouplist, const struct group_info * group_info)
```
</details>
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
