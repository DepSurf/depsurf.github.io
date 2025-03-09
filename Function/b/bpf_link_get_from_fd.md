# Function: <code>bpf_link_get_from_fd</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947296,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2464",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947296,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945488,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2480",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945488,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948128,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2488",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948128,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152784,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2598",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152784,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397680,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2847",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397680,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748128,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2881",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748128,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908160,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3000",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908160,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
```

```json
{
  "name": "bpf_link_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032400,
      "name": "bpf_link_get_from_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3064",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/mprog.c:bpf_mprog_tuple_relative",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032400,
      "name": "bpf_link_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct bpf_link * bpf_link_get_from_fd(u32 ufd)
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
