# Function: <code>ns_capable_setid</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526576,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526576,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552656,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552656,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585311,
      "name": "ns_capable_setid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579584704,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279106,
      "name": "ns_capable_setid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579564736,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221938,
      "name": "ns_capable_setid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579570192,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592101271,
      "name": "ns_capable_setid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579644128,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:432",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593868856,
      "name": "ns_capable_setid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071579739696,
      "name": "ns_capable_setid",
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870896,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:432",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870896,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919968,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:418",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919968,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959216,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:418",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/sys.c:__sys_setregid",
        "kernel/groups.c:__do_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959216,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490703712,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490703712,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224768348,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224768348,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283528352,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283528352,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271429940,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271429940,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528960,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528960,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579457760,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457760,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526240,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526240,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool ns_capable_setid(struct user_namespace * ns, int cap)
```

```json
{
  "name": "ns_capable_setid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559184,
      "name": "ns_capable_setid",
      "external": true,
      "loc": "kernel/capability.c:431",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559184,
      "name": "ns_capable_setid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool ns_capable_setid(struct user_namespace * ns, int cap)
```
</details>
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
