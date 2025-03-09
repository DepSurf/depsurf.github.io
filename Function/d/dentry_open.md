# Function: <code>dentry_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988464,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:861",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_create",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988464,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581143312,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:857",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_create",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143312,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581218496,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:874",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_create",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218496,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581265440,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:874",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265440,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404576,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:874",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404576,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581559376,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:916",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559376,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581639088,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:893",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639088,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755744,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:913",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755744,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827952,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827952,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049296,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:946",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049296,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098656,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:935",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098656,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123456,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:943",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123456,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440320,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:961",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440320,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956736,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:984",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956736,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514960,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:1016",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514960,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730432,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:1051",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730432,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931232,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:1090",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/ecryptfs/file.c:ecryptfs_dir_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931232,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493293392,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493293392,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226893456,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226893456,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286828656,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286828656,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273038020,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273038020,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796688,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796688,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734352,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734352,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581788000,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788000,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct file * dentry_open(const struct path * path, int flags, const struct cred * cred)
```

```json
{
  "name": "dentry_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581857136,
      "name": "dentry_open",
      "external": true,
      "loc": "fs/open.c:918",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/namespace.c:open_detached_copy",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_privileged_open",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/exportfs/expfs.c:get_name",
        "ipc/mqueue.c:do_mq_open",
        "security/keys/big_key.c:big_key_read",
        "security/apparmor/file.c:aa_inherit_files",
        "security/integrity/ima/ima_crypto.c:ima_calc_file_hash",
        "drivers/tty/pty.c:ptm_open_peer",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857136,
      "name": "dentry_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
