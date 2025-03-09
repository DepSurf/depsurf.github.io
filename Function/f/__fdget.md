# Function: <code>__fdget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581115040,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:761",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/kexec_file.c:copy_file_from_fd",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_event_get",
        "mm/readahead.c:SyS_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_fallocate",
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fchown",
        "fs/read_write.c:__compat_sys_preadv64",
        "fs/read_write.c:__compat_sys_pwritev64",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:SyS_pread64",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_preadv",
        "fs/read_write.c:SyS_pwritev",
        "fs/ioctl.c:SyS_ioctl",
        "fs/readdir.c:SyS_old_readdir",
        "fs/readdir.c:SyS_getdents",
        "fs/readdir.c:SyS_getdents64",
        "fs/select.c:do_select",
        "fs/select.c:do_sys_poll",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/sync.c:do_fsync",
        "fs/sync.c:SyS_syncfs",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/signalfd.c:SyS_signalfd",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:SyS_flock",
        "fs/compat.c:compat_SyS_old_readdir",
        "fs/compat.c:compat_SyS_getdents",
        "fs/compat.c:compat_SyS_getdents64",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115040,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581283110,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:762",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_ioctl",
        "mm/readahead.c:SyS_readahead",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fallocate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:SyS_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:do_fsync",
        "fs/sync.c:SyS_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:SyS_flock",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280752,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581361526,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:762",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_ioctl",
        "mm/readahead.c:SyS_readahead",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fallocate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:SyS_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:do_fsync",
        "fs/sync.c:SyS_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:SyS_flock",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359184,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581416790,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:748",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "mm/readahead.c:SyS_readahead",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fallocate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:SyS_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:do_fsync",
        "fs/sync.c:SyS_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:SyS_flock",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414448,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558310,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:751",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:sockmap_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "mm/readahead.c:SyS_readahead",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fallocate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:SyS_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:SyS_pwrite64",
        "fs/read_write.c:SyS_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:SyS_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:do_fsync",
        "fs/sync.c:SyS_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:SyS_flock",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556064,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581714917,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:747",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/bpf/sockmap.c:sockmap_get_from_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/readahead.c:ksys_readahead",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711232,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581801637,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:777",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797744,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581920469,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916592,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581992853,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988976,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582226869,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:808",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64",
        "fs/read_write.c:__x32_compat_sys_preadv64",
        "fs/read_write.c:__ia32_compat_sys_preadv64",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_offload_start",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222720,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582275301,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:944",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270240,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582300805,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:956",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_get_sq_data",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295744,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582619845,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:1016",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_get_sq_data",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614624,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583154837,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:1018",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_update_batch",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__do_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_sq_offload_create",
        "io_uring/io_uring.c:io_get_sq_data",
        "drivers/vfio/vfio.c:vfio_group_set_container",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150080,
      "name": "__fdget",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728501,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:1028",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__do_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/cancel.c:io_sync_cancel",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723408,
      "name": "__fdget",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583945557,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:1029",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/module/main.c:__ia32_sys_finit_module",
        "kernel/module/main.c:__x64_sys_finit_module",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/filemap.c:__ia32_sys_cachestat",
        "mm/filemap.c:__x64_sys_cachestat",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__do_sys_flock",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "io_uring/io_uring.c:__do_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/cancel.c:io_sync_cancel",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/net_namespace.c:get_net_ns_by_fd",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940464,
      "name": "__fdget",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152965,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:1158",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/pid.c:__ia32_sys_pidfd_getfd",
        "kernel/pid.c:__x64_sys_pidfd_getfd",
        "kernel/pid.c:pidfd_get_pid",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/module/main.c:__ia32_sys_finit_module",
        "kernel/module/main.c:__x64_sys_finit_module",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_link_get_from_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/watch_queue.c:get_watch_queue",
        "mm/filemap.c:__ia32_sys_cachestat",
        "mm/filemap.c:__x64_sys_cachestat",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:__do_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv",
        "fs/read_write.c:__ia32_sys_pwrite64",
        "fs/read_write.c:__x64_sys_pwrite64",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64",
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_select",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/kernel_read_file.c:kernel_read_file_from_fd",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/locks.c:__do_sys_flock",
        "fs/fhandle.c:handle_to_path",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "security/landlock/syscalls.c:get_ruleset_from_fd",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "net/socket.c:__sys_connect",
        "net/socket.c:__sys_accept4",
        "net/socket.c:sockfd_lookup_light",
        "net/core/net_namespace.c:get_net_ns_by_fd",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149616,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493508040,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/vfio.c:kvm_vfio_set_group",
        "virt/kvm/vfio.c:kvm_vfio_set_group",
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/xattr.c:__arm64_sys_fremovexattr",
        "fs/xattr.c:__arm64_sys_flistxattr",
        "fs/xattr.c:__arm64_sys_fgetxattr",
        "fs/xattr.c:__arm64_sys_fsetxattr",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:__arm64_sys_splice",
        "fs/splice.c:__arm64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__arm64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/locks.c:__arm64_sys_flock",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493502232,
      "name": "__fdget",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227064580,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__se_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/locks.c:__se_sys_flock",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:__se_sys_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227060760,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287071824,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__se_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/locks.c:__se_sys_flock",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287065536,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273180178,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:__se_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__se_sys_splice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__se_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/locks.c:__se_sys_flock",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273175034,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961589,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957712,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899157,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895280,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581952901,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949024,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int __fdget(unsigned int fd)
```

```json
{
  "name": "__fdget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023125,
      "name": "__fdget",
      "external": true,
      "loc": "fs/file.c:783",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__fdget_pos"
      ],
      "caller_func": [
        "kernel/exit.c:kernel_waitid",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:__bpf_prog_get",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/btf.c:btf_get_by_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_perf_ioctl",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/open.c:ksys_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_pwritev",
        "fs/read_write.c:do_preadv",
        "fs/read_write.c:ksys_pwrite64",
        "fs/read_write.c:ksys_pread64",
        "fs/exec.c:kernel_read_file_from_fd",
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/sync.c:ksys_sync_file_range",
        "fs/sync.c:do_fsync",
        "fs/sync.c:__ia32_sys_syncfs",
        "fs/sync.c:__x64_sys_syncfs",
        "fs/utimes.c:do_utimes",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/timerfd.c:timerfd_fget",
        "fs/eventfd.c:eventfd_ctx_fdget",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/locks.c:__ia32_sys_flock",
        "fs/locks.c:__x64_sys_flock",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/fhandle.c:do_handle_open",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "net/socket.c:sockfd_lookup_light",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020912,
      "name": "__fdget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
