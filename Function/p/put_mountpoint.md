# Function: <code>put_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581122128,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:unhash_mnt",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:SyS_pivot_root"
      ],
      "caller_func": [
        "fs/namespace.c:unhash_mnt",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:SyS_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122128,
      "name": "put_mountpoint.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581304857,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:unhash_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287872,
      "name": "put_mountpoint.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581383844,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:771",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367040,
      "name": "put_mountpoint.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439110,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:772",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421872,
      "name": "put_mountpoint.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581580998,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:832",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563376,
      "name": "put_mountpoint.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void put_mountpoint(struct mountpoint * mp)
```

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581720640,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:842",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720640,
      "name": "put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void put_mountpoint(struct mountpoint * mp)
```

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581807440,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:754",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:unhash_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807440,
      "name": "put_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581947431,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582020007,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255606,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:786",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582304902,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:786",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582332500,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:800",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582653092,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:802",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583192231,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:845",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583767591,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:956",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583984758,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:865",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584197302,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:853",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493541904,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227093084,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287112536,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:umount_mnt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273206864,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581988743,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581926311,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581980023,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582050517,
      "name": "put_mountpoint",
      "external": false,
      "loc": "fs/namespace.c:770",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mnt_change_mountpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void put_mountpoint(struct mountpoint * mp)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void put_mountpoint(struct mountpoint * mp)
```
</details>
</li>
</ul>
