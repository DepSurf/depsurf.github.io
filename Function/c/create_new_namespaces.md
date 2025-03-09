# Function: <code>create_new_namespaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504304,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:63",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:copy_namespaces",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:SyS_setns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504304,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518352,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:63",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518352,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542000,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:63",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542000,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528624,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:64",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528624,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555104,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:64",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:SyS_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555104,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583120,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:64",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583120,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620320,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:64",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620320,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644944,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644944,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682080,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682080,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720288,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720288,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698496,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698496,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705632,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705632,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783776,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783776,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889744,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889744,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040512,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040512,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094480,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094480,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138848,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:67",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/nsproxy.c:exec_task_namespaces",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138848,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490857000,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__arm64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490857000,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224877068,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224877068,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283686272,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283686272,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271515886,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__se_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271515886,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658400,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658400,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586752,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586752,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655664,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655664,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
struct nsproxy * create_new_namespaces(long unsigned int flags, struct task_struct * tsk, struct user_namespace * user_ns, struct fs_struct * new_fs)
```

```json
{
  "name": "create_new_namespaces",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689520,
      "name": "create_new_namespaces",
      "external": false,
      "loc": "kernel/nsproxy.c:60",
      "file": "kernel/nsproxy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__ia32_sys_setns",
        "kernel/nsproxy.c:__x64_sys_setns",
        "kernel/nsproxy.c:unshare_nsproxy_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689520,
      "name": "create_new_namespaces",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
