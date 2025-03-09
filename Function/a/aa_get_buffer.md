# Function: <code>aa_get_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1702",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110091,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584109600,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1702",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591368611,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584228848,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1712",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311283,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584253904,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1712",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592306343,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071584639584,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1952",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087888,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585295856,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2051",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100748,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586032480,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2207",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596624017,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586267792,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
char * aa_get_buffer(bool in_atomic)
```

```json
{
  "name": "aa_get_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_get_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2220",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/file.c:__file_mqueue_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597530405,
      "name": "aa_get_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586524464,
      "name": "aa_get_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
char * aa_get_buffer(bool in_atomic)
```
</details>
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
