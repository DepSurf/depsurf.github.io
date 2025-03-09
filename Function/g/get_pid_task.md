# Function: <code>get_pid_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491280,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:476",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:oom_adj_write",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:seq_show",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_follow_link",
        "fs/proc/namespaces.c:proc_ns_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491280,
      "name": "get_pid_task",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505200,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:476",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505200,
      "name": "get_pid_task",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525872,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:476",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525872,
      "name": "get_pid_task",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513552,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:477",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513552,
      "name": "get_pid_task",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540272,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540272,
      "name": "get_pid_task",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567936,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:371",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567936,
      "name": "get_pid_task",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605120,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:378",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605120,
      "name": "get_pid_task",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629008,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629008,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654560,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654560,
      "name": "get_pid_task",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687077,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:447",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686528,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665349,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:448",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665200,
      "name": "get_pid_task",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672181,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:448",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671632,
      "name": "get_pid_task",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749477,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:448",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_fdinfo_open",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749168,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579854056,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:448",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853680,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995000,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:448",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994592,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049464,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:451",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048416,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091960,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:451",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/pid.c:pidfd_get_task"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/base.c:timens_offsets_show",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:lstats_write",
        "fs/proc/base.c:lstats_show_proc",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/fd.c:proc_readfd_count",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090912,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490828008,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_yield_to",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828008,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859668,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859668,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283661664,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_cmdline_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661664,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271499678,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499678,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630880,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630880,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559216,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559216,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628144,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628144,
      "name": "get_pid_task",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct task_struct * get_pid_task(struct pid * pid, enum pid_type type)
```

```json
{
  "name": "get_pid_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662208,
      "name": "get_pid_task",
      "external": true,
      "loc": "kernel/pid.c:381",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_task_getattr",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_tid_comm_permission",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_coredump_filter_write",
        "fs/proc/base.c:proc_coredump_filter_read",
        "fs/proc/base.c:proc_pid_attr_read",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:proc_pident_lookup",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:timers_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:comm_show",
        "fs/proc/base.c:comm_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:sched_autogroup_show",
        "fs/proc/base.c:sched_write",
        "fs/proc/base.c:sched_show",
        "fs/proc/base.c:proc_sessionid_read",
        "fs/proc/base.c:proc_loginuid_read",
        "fs/proc/base.c:oom_score_adj_read",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:oom_adj_read",
        "fs/proc/base.c:proc_mem_open",
        "fs/proc/base.c:proc_single_show",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:lstats_write",
        "fs/proc/base.c:lstats_show_proc",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show",
        "fs/proc/namespaces.c:proc_ns_dir_lookup",
        "fs/proc/namespaces.c:proc_ns_dir_readdir",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662208,
      "name": "get_pid_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
