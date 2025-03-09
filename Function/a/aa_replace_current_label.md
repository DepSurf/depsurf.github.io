# Function: <code>aa_replace_current_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479472,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/context.c:94",
      "file": "security/apparmor/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479472,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582711760,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/context.c:94",
      "file": "security/apparmor/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582711760,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806352,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/context.c:94",
      "file": "security/apparmor/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:ns_rmdir_op",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked",
        "security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806352,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895248,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/context.c:82",
      "file": "security/apparmor/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895248,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583053648,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/context.c:82",
      "file": "security/apparmor/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583053648,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583254544,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:45",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254544,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372144,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:45",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372144,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583559152,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559152,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664880,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664880,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026416,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026416,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145856,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145856,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173024,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173024,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557968,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557968,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201728,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:46",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201728,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585933424,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:46",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585933424,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165792,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:46",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/lsm.c:begin_current_label_crit_section",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165792,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586415568,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:46",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/apparmorfs.c:begin_current_label_crit_section",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_inode_create",
        "security/apparmor/lsm.c:apparmor_inode_create",
        "security/apparmor/lsm.c:apparmor_inode_create",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_unix.c:begin_current_label_crit_section",
        "security/apparmor/af_inet.c:begin_current_label_crit_section",
        "security/apparmor/af_inet.c:begin_current_label_crit_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415568,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495458072,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495458072,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228824968,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228824968,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289508736,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289508736,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274646616,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274646616,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633616,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633616,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570672,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570672,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617392,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617392,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
int aa_replace_current_label(struct aa_label * label)
```

```json
{
  "name": "aa_replace_current_label",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715328,
      "name": "aa_replace_current_label",
      "external": true,
      "loc": "security/apparmor/task.c:41",
      "file": "security/apparmor/task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/net.c:aa_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715328,
      "name": "aa_replace_current_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
