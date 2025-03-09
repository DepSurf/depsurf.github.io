# Function: <code>percpu_down_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_down_write(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672896,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:124",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672896,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void percpu_down_write(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691776,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:125",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691776,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719632,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:141",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719632,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715328,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:140",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715328,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747968,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:140",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747968,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782352,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:140",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782352,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828912,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:140",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:__remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828912,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863550,
      "name": "percpu_down_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579863328,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912032,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912032,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956160,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:214",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956160,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944320,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:214",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944320,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952048,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:214",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952048,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080880,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:214",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080880,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594728896,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:218",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594728896,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596480560,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:224",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480560,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597022112,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:224",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597022112,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597951456,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:224",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597951456,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491115312,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115312,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225117392,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117392,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284006656,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284006656,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271692128,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692128,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884144,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884144,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819120,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819120,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872304,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872304,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void percpu_down_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917824,
      "name": "percpu_down_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:143",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_start",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917824,
      "name": "percpu_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_rw_semaphore * sem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_rw_semaphore * brw</code>
</li>
</ul>
</details>
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
