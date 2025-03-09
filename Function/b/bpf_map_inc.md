# Function: <code>bpf_map_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365936,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:184",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365936,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423152,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:229",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423152,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471296,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:272",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471296,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580491392,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:338",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491392,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580546480,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:469",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546480,
      "name": "bpf_map_inc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628448,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:545",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628448,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687552,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:601",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687552,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580754704,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:658",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754704,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805296,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805296,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938220,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:911",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922768,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580934956,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:924",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919024,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937660,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:925",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922928,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581141516,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:952",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125488,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404496,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1186",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396608,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756800,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1229",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746784,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581916963,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906528,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_map_inc(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582043331,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1335",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/arraymap.c:prog_array_map_clear",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030768,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492122280,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492122280,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226022536,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226022536,
      "name": "bpf_map_inc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3226022588,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285328784,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285328784,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272301536,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272291644,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580774096,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774096,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580720272,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720272,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765344,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765344,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_map * bpf_map_inc(struct bpf_map * map, bool uref)
```

```json
{
  "name": "bpf_map_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580823504,
      "name": "bpf_map_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:661",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823504,
      "name": "bpf_map_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct bpf_map *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool uref</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_map *</code> ➡️ <code>void</code>
</li>
</ul>
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
