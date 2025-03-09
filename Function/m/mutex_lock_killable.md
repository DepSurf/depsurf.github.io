# Function: <code>mutex_lock_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587372480,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:801",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "fs/readdir.c:iterate_dir",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/access.c:pci_vpd_pci22_write",
        "drivers/pci/access.c:pci_vpd_pci22_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372480,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587873312,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:805",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/access.c:pci_vpd_write",
        "drivers/pci/access.c:pci_vpd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873312,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588088816,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:942",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/access.c:pci_vpd_write",
        "drivers/pci/access.c:pci_vpd_read",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088816,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315488,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/access.c:pci_vpd_write",
        "drivers/pci/access.c:pci_vpd_read",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315488,
      "name": "mutex_lock_killable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880960,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/access.c:pci_vpd_write",
        "drivers/pci/access.c:pci_vpd_read",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880960,
      "name": "mutex_lock_killable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261296,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1121",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:lo_compat_ioctl",
        "drivers/block/loop.c:lo_compat_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261296,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503792,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1299",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503792,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964480,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1304",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964480,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192144,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192144,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591208000,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_pid_stack",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_get_status_compat",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status_old",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208000,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591703200,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1333",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_get_status_compat",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status_old",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591703200,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591643488,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1331",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_open",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591643488,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592817136,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:945",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:lo_open",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592817136,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594724032,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1001",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594724032,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596474384,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1001",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596474384,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597012944,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1001",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597012944,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597942288,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1006",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_get_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597942288,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503932808,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503932808,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236546428,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236546428,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297785280,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297785280,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279803284,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279803284,
      "name": "mutex_lock_killable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589794432,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794432,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516912,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516912,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590237840,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590237840,
      "name": "mutex_lock_killable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_killable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590285872,
      "name": "mutex_lock_killable",
      "external": true,
      "loc": "kernel/locking/mutex.c:1330",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/percpu.c:pcpu_alloc",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "fs/proc/base.c:do_io_accounting",
        "drivers/pci/vpd.c:pci_vpd_write",
        "drivers/pci/vpd.c:pci_vpd_read",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd",
        "net/core/rtnetlink.c:rtnl_lock_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285872,
      "name": "mutex_lock_killable",
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
