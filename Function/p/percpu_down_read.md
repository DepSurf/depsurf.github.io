# Function: <code>percpu_down_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_down_read(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672752,
      "name": "percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:70",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672752,
      "name": "percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_down_read(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691632,
      "name": "percpu_down_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:71",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691632,
      "name": "percpu_down_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393239,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579469975,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591497,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240334,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581256892,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581855992,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579379436,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579395777,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458354,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580621545,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123727,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287698,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581306099,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582003954,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:56",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407593,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423521,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486594,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702457,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236335,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427234,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581445762,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582153954,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422464,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579438213,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504002,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834869,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383589,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582093,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581607270,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582319103,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579453990,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579471173,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537858,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903301,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467813,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668429,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581692229,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582418271,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:57",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472345,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488965,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555203,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001013,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583333,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785858,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581813569,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246862,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588253,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579498449,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514901,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581347,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354133,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055861,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648005,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581858130,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581886145,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582346686,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689005,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543733,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616853,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580384707,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428837,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237829,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861893,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082786,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582113655,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638122,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000944,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525445,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597125,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371683,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416357,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280597,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313984,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906069,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097394,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124788,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582160007,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290131,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379363,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410688,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528056,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613106,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710202,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_delete_lease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749827,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583023403,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115580,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175016,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583679964,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221164,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579529109,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602597,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374691,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419141,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297077,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333024,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753765,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122194,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149589,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184087,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317267,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406317,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437488,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556864,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636238,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739530,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778868,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049069,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141276,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201560,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704588,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109180,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601205,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677749,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580535859,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582405,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542229,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580688,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034949,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439042,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466453,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501495,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637619,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728093,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760272,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582873040,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957807,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066442,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106076,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386676,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481804,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544763,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065207,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680476,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579693557,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579781765,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580733219,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783333,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892837,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932321,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464677,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958153,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986452,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583022505,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174195,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273697,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311378,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437365,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544428,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588036,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583900678,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006016,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078411,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584656345,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586018920,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589031273,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579817573,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914453,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009123,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066597,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305923,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582326309,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370779,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978517,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516441,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546818,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583833,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749203,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856081,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583896322,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584027077,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145404,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192339,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526163,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636141,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711227,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585338166,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859715,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559685,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579865589,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964245,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097715,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506195,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582527541,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575630,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190037,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731958,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762825,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583800793,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965747,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077031,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118264,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584253246,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372687,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419883,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483657,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755209,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859556,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935426,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568108,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125958,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590888087,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903493,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003557,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195139,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674739,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582696453,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744574,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583375189,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932744,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965514,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006997,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584165651,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293178,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335914,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470462,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584591151,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619313,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/backing-file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640700,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706617,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987945,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092484,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166994,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806444,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587405184,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:47",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490630768,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490651728,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490744748,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491613672,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492413920,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493096264,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493327124,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493361600,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493930768,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494343840,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224709192,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224728176,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 3224795436,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 3225570932,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226297616,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226926432,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226947368,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3227409592,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227805164,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283450308,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283473576,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283569088,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605388,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285680268,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286545924,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286872888,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286905080,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287575696,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288073896,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271386216,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271449886,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272015956,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273059578,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273081502,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273481784,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273775328,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472113,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488565,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557651,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322933,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024709,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616741,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826866,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581854881,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315422,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657741,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401025,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417445,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486323,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270213,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970805,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558069,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764530,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581789638,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253182,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582594909,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472033,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488485,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554931,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314181,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015909,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608053,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581818178,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581846193,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305902,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647597,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_down_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503819,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520789,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588145,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369093,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077173,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672437,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890174,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581915212,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385100,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731501,
      "name": "percpu_down_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:36",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void percpu_down_read(struct percpu_rw_semaphore * brw)
```
</details>
</li>
</ul>
