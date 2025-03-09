# Function: <code>__bpf_map_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363387,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:172",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365856,
      "name": "__bpf_map_get",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424488,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:214",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423072,
      "name": "__bpf_map_get",
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580474291,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:257",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471216,
      "name": "__bpf_map_get",
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580493918,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:323",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491312,
      "name": "__bpf_map_get",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549125,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:454",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546400,
      "name": "__bpf_map_get",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580627268,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:530",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/sockmap.c:sockmap_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636752,
      "name": "__bpf_map_get",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696622,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:586",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693920,
      "name": "__bpf_map_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768382,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:643",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764080,
      "name": "__bpf_map_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580820341,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815024,
      "name": "__bpf_map_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930520,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:899",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938064,
      "name": "__bpf_map_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927144,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:912",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934800,
      "name": "__bpf_map_get",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949451,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:913",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937504,
      "name": "__bpf_map_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581154388,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:940",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141360,
      "name": "__bpf_map_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406027,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1174",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416192,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581781995,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1217",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772800,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919046,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1292",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934400,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582045446,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1323",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/syscall.c:bpf_map_get"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_bpf_prog_query",
        "net/core/sock_map.c:sock_map_prog_detach",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061024,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492135680,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref",
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492135680,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226038708,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226034280,
      "name": "__bpf_map_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285349440,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285344144,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272304710,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272301330,
      "name": "__bpf_map_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789141,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783824,
      "name": "__bpf_map_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735317,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730000,
      "name": "__bpf_map_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780389,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775072,
      "name": "__bpf_map_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_get(struct fd f)
```

```json
{
  "name": "__bpf_map_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838636,
      "name": "__bpf_map_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:646",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:bpf_map_get_with_uref"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "net/core/sock_map.c:sock_map_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833328,
      "name": "__bpf_map_get",
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
