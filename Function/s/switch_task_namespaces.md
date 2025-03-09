# Function: <code>switch_task_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505248,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:216",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:exit_task_namespaces",
        "kernel/nsproxy.c:SyS_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505248,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519376,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:216",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519376,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543024,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:216",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543024,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529552,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:217",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529552,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556048,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:217",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556048,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584064,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:217",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584064,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621264,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:217",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621264,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645920,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645920,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683056,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683056,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722688,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:242",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722688,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701088,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701088,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708224,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708224,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786368,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786368,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892432,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:237",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892432,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043312,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:239",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043312,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097328,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:239",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097328,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580143238,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:239",
      "file": "kernel/nsproxy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:exit_task_namespaces"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__do_sys_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141888,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490858080,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__arm64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490858080,
      "name": "switch_task_namespaces",
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224878068,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224878068,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283687904,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283687904,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271516748,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271516748,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659376,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659376,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587728,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587728,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656640,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656640,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void switch_task_namespaces(struct task_struct * p, struct nsproxy * new)
```

```json
{
  "name": "switch_task_namespaces",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690512,
      "name": "switch_task_namespaces",
      "external": true,
      "loc": "kernel/nsproxy.c:213",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:exit_task_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690512,
      "name": "switch_task_namespaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
