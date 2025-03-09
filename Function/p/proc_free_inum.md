# Function: <code>proc_free_inum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462976,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:220",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/generic.c:pde_put",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462976,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647360,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:224",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/generic.c:pde_put",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647360,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735664,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:224",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/generic.c:pde_put",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735664,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790930,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:210",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:pde_put"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790672,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581940291,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:212",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:pde_put"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940032,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123798,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:217",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123296,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218252,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:217",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217744,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382458,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381904,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582481370,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480816,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582779871,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:220",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779424,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582853167,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:220",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852720,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881512,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:215",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880880,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583215128,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:215",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214496,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712368,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:215",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711664,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584323792,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:215",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323040,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553777,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:214",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552992,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785633,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:214",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784848,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494102900,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494102176,
      "name": "proc_free_inum",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227552804,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227552168,
      "name": "proc_free_inum",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287771304,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:put_pid_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287770480,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273589498,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273588330,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582450106,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449552,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387274,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386720,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440586,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440032,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void proc_free_inum(unsigned int inum)
```

```json
{
  "name": "proc_free_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582520772,
      "name": "proc_free_inum",
      "external": true,
      "loc": "fs/proc/generic.c:218",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520208,
      "name": "proc_free_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
