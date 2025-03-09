# Function: <code>proc_alloc_inum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462752,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:193",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462752,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647136,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:197",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647136,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735440,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:197",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735440,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581788982,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:197",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790608,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938454,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:199",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939968,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123541,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:204",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123232,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582217989,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:204",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217680,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382149,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381840,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582481061,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480752,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582779733,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:207",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779360,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582853048,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:207",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852656,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881214,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:202",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880816,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214830,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:202",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214432,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712073,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:202",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711584,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584323497,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:202",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322944,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553513,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:201",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552896,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785369,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:201",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784752,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494102668,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494102096,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227552500,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227552100,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287770936,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287770368,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273589254,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273588254,
      "name": "proc_alloc_inum",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582449797,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449488,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582386965,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386656,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440277,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439968,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int proc_alloc_inum(unsigned int * inum)
```

```json
{
  "name": "proc_alloc_inum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582520453,
      "name": "proc_alloc_inum",
      "external": true,
      "loc": "fs/proc/generic.c:205",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/proc/self.c:proc_self_init",
        "fs/proc/thread_self.c:proc_thread_self_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:net_ns_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520144,
      "name": "proc_alloc_inum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
