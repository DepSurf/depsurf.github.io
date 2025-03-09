# Function: <code>kern_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057888,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2252",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057888,
      "name": "kern_path",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218784,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2389",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218784,
      "name": "kern_path",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296480,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2378",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296480,
      "name": "kern_path",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346048,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346048,
      "name": "kern_path",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487440,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2421",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487440,
      "name": "kern_path",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647472,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2408",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647472,
      "name": "kern_path",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733744,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2432",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733744,
      "name": "kern_path",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853136,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2430",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853136,
      "name": "kern_path",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925600,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925600,
      "name": "kern_path",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155840,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2451",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155840,
      "name": "kern_path",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201344,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/block_dev.c:lookup_bdev",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201344,
      "name": "kern_path",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226112,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2539",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/block_dev.c:lookup_bdev",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226112,
      "name": "kern_path",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543152,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2565",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "block/bdev.c:lookup_bdev",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543152,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583070848,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2611",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "block/bdev.c:lookup_bdev",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070848,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583637248,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2590",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "block/bdev.c:lookup_bdev",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637248,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854400,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2603",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount_old",
        "security/apparmor/mount.c:aa_bind_mount",
        "block/bdev.c:lookup_bdev",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854400,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061584,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2620",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/init.c:init_utimes",
        "fs/init.c:init_link",
        "fs/init.c:init_stat",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chmod",
        "fs/init.c:init_chown",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/init.c:init_umount",
        "fs/init.c:init_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount_old",
        "security/apparmor/mount.c:aa_bind_mount",
        "block/bdev.c:lookup_bdev",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061584,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493406136,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493406136,
      "name": "kern_path",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226991984,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226991984,
      "name": "kern_path",
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286964576,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286964576,
      "name": "kern_path",
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
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273117438,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273117438,
      "name": "kern_path",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894336,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894336,
      "name": "kern_path",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831936,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831936,
      "name": "kern_path",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885648,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885648,
      "name": "kern_path",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int kern_path(const char * name, unsigned int flags, struct path * path)
```

```json
{
  "name": "kern_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955152,
      "name": "kern_path",
      "external": true,
      "loc": "fs/namei.c:2423",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/trace/trace_uprobe.c:create_local_trace_uprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_set_filter",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "security/tomoyo/load_policy.c:tomoyo_load_policy",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/tomoyo/realpath.c:tomoyo_realpath_nofollow",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955152,
      "name": "kern_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
