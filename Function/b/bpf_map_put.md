# Function: <code>bpf_map_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364416,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:96",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_release",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364416,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421568,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:111",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_release",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421568,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580470848,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:139",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_release",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470848,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580496892,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:191",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491184,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553811,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:241",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546192,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580636651,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:287",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635104,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580702676,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:315",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693424,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580769689,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:333",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:free_used_maps",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762368,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819336,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812432,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580936576,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:490",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_free_used_maps",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928608,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938643,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:484",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925536,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941347,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:485",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928928,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581145299,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:504",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132512,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581420399,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:625",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404384,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581757039,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:725",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756672,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911296,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:722",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_dealloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911296,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582036016,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:750",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_free_used_maps",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release",
        "kernel/bpf/map_iter.c:bpf_map_seq_next",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_dealloc",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_update_elem",
        "net/xdp/xskmap.c:xsk_map_sock_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597434323,
      "name": "bpf_map_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582035984,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492144260,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492133296,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226039840,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031656,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285340496,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285340336,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272299184,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:bpf_map_put_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299022,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788136,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781232,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734312,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727408,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580779384,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772480,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_map_put(struct bpf_map * map)
```

```json
{
  "name": "bpf_map_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837672,
      "name": "bpf_map_put",
      "external": true,
      "loc": "kernel/bpf/syscall.c:336",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_release"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830704,
      "name": "bpf_map_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
