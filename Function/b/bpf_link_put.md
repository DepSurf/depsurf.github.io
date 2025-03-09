# Function: <code>bpf_link_put</code>

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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945180,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2328",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_link_get_fd_by_id",
        "kernel/bpf/syscall.c:link_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945632,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580942300,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2344",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:link_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942768,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944780,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2352",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945248,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581148924,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2462",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149392,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581424300,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2710",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/link_iter.c:bpf_link_seq_next",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424112,
      "name": "bpf_link_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581758460,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2744",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_release",
        "kernel/bpf/syscall.c:bpf_link_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/link_iter.c:bpf_link_seq_next",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755760,
      "name": "bpf_link_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914400,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2857",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/link_iter.c:bpf_link_seq_next",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914400,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void bpf_link_put(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582040080,
      "name": "bpf_link_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2921",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_free_inode",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/link_iter.c:bpf_link_seq_next",
        "kernel/bpf/mprog.c:bpf_mprog_detach",
        "kernel/bpf/mprog.c:bpf_mprog_attach",
        "kernel/bpf/mprog.c:bpf_mprog_tuple_relative",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040080,
      "name": "bpf_link_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void bpf_link_put(struct bpf_link * link)
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
