# Function: <code>percpu_up_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_up_read(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672832,
      "name": "percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:98",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "fs/super.c:__sb_end_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672832,
      "name": "percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void percpu_up_read(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_up_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691712,
      "name": "percpu_up_read",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:99",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "fs/super.c:__sb_end_write",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691712,
      "name": "percpu_up_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393291,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579470047,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591557,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238072,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257335,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581856086,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579379489,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579395813,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
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
      "addr": 18446744071579458426,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580621605,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123803,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285444,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306514,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582004046,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:104",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407650,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423557,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
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
      "addr": 18446744071579486666,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702521,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236411,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424840,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446184,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582154046,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579413808,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579432181,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504074,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834933,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383413,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581861,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607692,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582319167,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579446576,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579465717,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537930,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903365,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467637,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668197,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692667,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582418335,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:105",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579462960,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483573,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555280,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001077,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583157,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785599,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814002,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246976,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582588320,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579489632,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579509557,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581424,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354197,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055925,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647829,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857839,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886578,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582346800,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582689072,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543781,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579616934,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580384964,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428901,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237893,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861975,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082520,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114065,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638235,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071583001005,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525493,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579597206,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580310889,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371940,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416421,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280661,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314092,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906151,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097299,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124536,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071582160417,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166237,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266364,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280313,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379330,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410732,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537522,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557943,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710315,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071582749794,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019341,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115702,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175154,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297301,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583679995,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221196,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579529157,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579602678,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314265,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374944,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419205,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297141,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333127,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753847,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122099,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149254,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071582184497,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189968,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291692,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305631,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406284,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437532,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566818,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623987,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739643,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071582778440,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045149,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141398,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201698,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321429,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583704619,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109212,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601253,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579677830,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580467801,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536112,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582469,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542293,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580796,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035031,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438931,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466086,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071582501905,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507280,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610492,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624975,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728060,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760316,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883826,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955802,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066555,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071583105648,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382438,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481930,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544941,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665125,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584065238,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680508,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579693621,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579781858,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661329,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580733498,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783429,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892933,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932449,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464776,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957998,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986174,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071583022933,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030605,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143443,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583164158,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273639,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311450,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450334,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544560,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588100,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895689,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006164,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078629,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234171,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584656401,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585965969,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589031343,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579817637,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579914546,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931185,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009403,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066709,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305682,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582326421,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370967,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978616,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516286,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546522,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071583584261,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594861,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715411,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583739406,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856023,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583896394,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040990,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145536,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192244,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520909,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636286,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711440,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584877730,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585338222,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586855125,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590559755,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579865653,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071579964346,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017598,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068827,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505954,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582527653,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575813,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190136,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731784,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762501,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071583801221,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811549,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933139,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583956161,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076969,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118336,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584265713,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372819,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419788,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483706,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584749757,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859705,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935481,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104930,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585568164,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121416,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590888256,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903557,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071580003662,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113470,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166251,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674498,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582696565,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744754,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583375288,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932583,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965087,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
      "addr": 18446744071584007425,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017688,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139454,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164801,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293120,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335852,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482625,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584591283,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
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
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619644,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/backing-file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/backing-file.c:backing_aio_rw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640605,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706666,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982637,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092633,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167049,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337298,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585806500,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399774,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:97",
      "file": "io_uring/rw.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490620136,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446603336490651784,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446603336490744840,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491613760,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492414008,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493096352,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493327008,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493361964,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493930952,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446603336494343900,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490620136,
      "name": "percpu_up_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224701472,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 3224728240,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 3224795532,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571012,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226297700,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226923472,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3226947744,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3227409744,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 3227805268,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224701472,
      "name": "percpu_up_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283438144,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 13835058055283473652,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 13835058055283569184,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605520,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285680400,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286546044,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286867984,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286905492,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287575928,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 13835058055288073964,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283438144,
      "name": "percpu_up_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271379766,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446743936271449970,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272016052,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273059134,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273081374,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273481972,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446743936273775422,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271379766,
      "name": "percpu_up_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579463296,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483221,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557728,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322997,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024773,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616565,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826575,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855314,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315536,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582657808,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579392256,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579412101,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486400,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270277,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970869,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557893,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764239,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790065,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253296,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582594976,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579463216,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483141,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpus_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555008,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314245,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015973,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607877,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817887,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846626,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306016,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582647664,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
  "name": "percpu_up_read",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579495632,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579520848,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071579588237,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369173,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_read_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077253,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672530,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887539,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915657,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385226,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
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
      "addr": 18446744071582731583,
      "name": "percpu_up_read",
      "external": false,
      "loc": "include/linux/percpu-rwsem.h:84",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495632,
      "name": "percpu_up_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void percpu_up_read(struct percpu_rw_semaphore * brw)
```
</details>
</li>
</ul>
