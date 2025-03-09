# Function: <code>groups_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517584,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:51",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/groups.c:set_groups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/uid16.c:SyS_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517584,
      "name": "groups_free",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531728,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:51",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:set_groups",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/uid16.c:SyS_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531728,
      "name": "groups_free",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557646,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:32",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/uid16.c:SyS_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556752,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544100,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:33",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/uid16.c:SyS_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543408,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579571976,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:SyS_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:SyS_setgroups16",
        "kernel/uid16.c:SyS_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571248,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579600465,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599424,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579637477,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636512,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662300,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661328,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699372,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698400,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579739974,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738912,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579721382,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720320,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579728788,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727680,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579808836,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807728,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579919211,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917952,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073919,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072464,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126751,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125296,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171240,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:29",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__do_sys_setgroups16",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169536,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490881912,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__arm64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__arm64_sys_setgroups16",
        "kernel/uid16.c:__arm64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490880112,
      "name": "groups_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224897472,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__se_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224896524,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283714568,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283712768,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271532814,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/groups.c:set_current_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271531926,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675692,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674720,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579604028,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603056,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672924,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671952,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void groups_free(struct group_info * group_info)
```

```json
{
  "name": "groups_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579707052,
      "name": "groups_free",
      "external": true,
      "loc": "kernel/groups.c:34",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16",
        "net/ipv4/ping.c:ping_init_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706080,
      "name": "groups_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
