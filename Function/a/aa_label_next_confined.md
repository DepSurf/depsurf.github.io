# Function: <code>aa_label_next_confined</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557088,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:466",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/file.c:path_name",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557088,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797952,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:466",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797952,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893776,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:482",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893776,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582962192,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:485",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962192,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583124512,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:485",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124512,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330336,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:484",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330336,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448912,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:485",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448912,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633936,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:481",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633936,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740096,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740096,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127728,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127728,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246112,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246112,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269040,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269040,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655072,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655072,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585315696,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:477",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315696,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055536,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:477",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055536,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586290560,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:477",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290560,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586547232,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:483",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:apparmor_secmark_check",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547232,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495538304,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495538304,
      "name": "aa_label_next_confined",
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228903164,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:path_name",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228903164,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289622656,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289622656,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274713258,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274713258,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708832,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708832,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583645888,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645888,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692608,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692608,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int aa_label_next_confined(struct aa_label * label, int i)
```

```json
{
  "name": "aa_label_next_confined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792496,
      "name": "aa_label_next_confined",
      "external": true,
      "loc": "security/apparmor/label.c:475",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/capability.c:aa_capable",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/lsm.c:apparmor_capget",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:__aa_transition_rlimits",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/resource.c:aa_task_setrlimit",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792496,
      "name": "aa_label_next_confined",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
