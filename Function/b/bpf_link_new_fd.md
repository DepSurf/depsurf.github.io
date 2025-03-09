# Function: <code>bpf_link_new_fd</code>

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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945888,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2459",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_link_get_fd_by_id"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947248,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947545,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2475",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945440,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950304,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2483",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948080,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581155578,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2593",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152736,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581431686,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2842",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432544,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581784768,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2876",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785776,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581946034,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2995",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946944,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int bpf_link_new_fd(struct bpf_link * link)
```

```json
{
  "name": "bpf_link_new_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582072494,
      "name": "bpf_link_new_fd",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3059",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073408,
      "name": "bpf_link_new_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int bpf_link_new_fd(struct bpf_link * link)
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
