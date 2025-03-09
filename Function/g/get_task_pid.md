# Function: <code>get_task_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491232,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:464",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitpid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491232,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505152,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:464",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitpid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505152,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525824,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:464",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitpid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525824,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513504,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:465",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513504,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540208,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:334",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540208,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567888,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:359",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567888,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605056,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:368",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605056,
      "name": "get_task_pid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629728,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629728,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655280,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655280,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686240,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:437",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686240,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664528,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664528,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671344,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671344,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749024,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749024,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853504,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853504,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994400,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994400,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048224,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048224,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090720,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid_prepare",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090720,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490828120,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828120,
      "name": "get_task_pid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859760,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859760,
      "name": "get_task_pid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283661568,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661568,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271499606,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499606,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631600,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631600,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559936,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559936,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628864,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628864,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pid * get_task_pid(struct task_struct * task, enum pid_type type)
```

```json
{
  "name": "get_task_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662608,
      "name": "get_task_pid",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "fs/proc/base.c:proc_pid_make_inode",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662608,
      "name": "get_task_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
