# Function: <code>find_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420464,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:146",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setpriority",
        "kernel/sys.c:SyS_getpriority",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420464,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432864,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:146",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432864,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453216,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:146",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453216,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441168,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:147",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441168,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469472,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469472,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483616,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:154",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483616,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516896,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:154",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516896,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536560,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536560,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562624,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562624,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594640,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594640,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574608,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574608,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580304,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580304,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654448,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:167",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654448,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750176,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:167",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750176,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882224,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:167",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882224,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931424,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:167",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931424,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970736,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:180",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970736,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490722016,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_getpriority",
        "kernel/sys.c:__arm64_sys_setpriority",
        "block/ioprio.c:__arm64_sys_ioprio_get",
        "block/ioprio.c:__arm64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490722016,
      "name": "find_user",
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224777624,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224777624,
      "name": "find_user",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283544608,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283544608,
      "name": "find_user",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271437248,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271437248,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538928,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538928,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467696,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467696,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536208,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536208,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct user_struct * find_user(kuid_t uid)
```

```json
{
  "name": "find_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569232,
      "name": "find_user",
      "external": true,
      "loc": "kernel/user.c:153",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569232,
      "name": "find_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
