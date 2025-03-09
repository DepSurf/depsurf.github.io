# Function: <code>aa_put_buffer</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609280028,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1743",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:alloc_buffers",
        "security/apparmor/lsm.c:alloc_buffers"
      ],
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
      "addr": 18446744071584109872,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612348857,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1743",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:alloc_buffers",
        "security/apparmor/lsm.c:alloc_buffers"
      ],
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
      "addr": 18446744071584229120,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614489814,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1753",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:alloc_buffers",
        "security/apparmor/lsm.c:alloc_buffers"
      ],
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
      "addr": 18446744071584254176,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615436776,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1753",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:alloc_buffers",
        "security/apparmor/lsm.c:alloc_buffers"
      ],
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
      "addr": 18446744071584639872,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617234459,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:1993",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init"
      ],
      "caller_func": [
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
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
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
      "addr": 18446744071585296144,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033152,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2116",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:alloc_buffers",
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
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
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
      "addr": 18446744071586033152,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268448,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2272",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:alloc_buffers",
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
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
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
      "addr": 18446744071586268448,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void aa_put_buffer(char * buf)
```

```json
{
  "name": "aa_put_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586525056,
      "name": "aa_put_buffer",
      "external": true,
      "loc": "security/apparmor/lsm.c:2283",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/ipc.c:aa_mqueue_perm",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:alloc_buffers",
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
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
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
      "addr": 18446744071586525056,
      "name": "aa_put_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void aa_put_buffer(char * buf)
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
