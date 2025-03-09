# Function: <code>percpu_up_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672704,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:147",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672704,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void percpu_up_write(struct percpu_rw_semaphore * brw)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691584,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:148",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691584,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719344,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:167",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719344,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715120,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:166",
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
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715120,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747744,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:166",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:thaw_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747744,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782128,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:166",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782128,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828688,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:166",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:__remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828688,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863104,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863104,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911808,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911808,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955568,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:242",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955568,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943728,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:242",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943728,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951472,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:242",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951472,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080320,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:242",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080320,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215520,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:248",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215520,
      "name": "percpu_up_write",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408208,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:254",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408208,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476976,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:254",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476976,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536800,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:254",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
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
      "addr": 18446744071580536800,
      "name": "percpu_up_write",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491115184,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491115184,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225117656,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225117656,
      "name": "percpu_up_write",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284007008,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284007008,
      "name": "percpu_up_write",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271692326,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692326,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883920,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883920,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818896,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818896,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872080,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872080,
      "name": "percpu_up_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void percpu_up_write(struct percpu_rw_semaphore * sem)
```

```json
{
  "name": "percpu_up_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917600,
      "name": "percpu_up_write",
      "external": true,
      "loc": "kernel/locking/percpu-rwsem.c:169",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_finish",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_s64",
        "kernel/cgroup/cpuset.c:cpuset_write_u64",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_cancel_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:thaw_super_locked",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/super.c:freeze_super",
        "fs/locks.c:locks_stop",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917600,
      "name": "percpu_up_write",
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
