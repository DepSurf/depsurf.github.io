# Function: <code>bpf_prog_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421284,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:683",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424032,
      "name": "bpf_prog_inc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580469732,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:779",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469584,
      "name": "bpf_prog_inc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490043,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:866",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489888,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545406,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1035",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543088,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630177,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1136",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628592,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688801,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1322",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687696,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580756225,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1459",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754848,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806481,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805440,
      "name": "bpf_prog_inc",
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928303,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1863",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922864,
      "name": "bpf_prog_inc",
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580925058,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1837",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919120,
      "name": "bpf_prog_inc",
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928418,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1845",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923024,
      "name": "bpf_prog_inc",
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581152322,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1939",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125584,
      "name": "bpf_prog_inc",
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581427441,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2185",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396720,
      "name": "bpf_prog_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581780081,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2219",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746944,
      "name": "bpf_prog_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942289,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2298",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906688,
      "name": "bpf_prog_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582069104,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2338",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/bpf_iter.c:prepare_seq_file",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_event_alloc",
        "net/core/dev.c:dev_xdp_install",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030928,
      "name": "bpf_prog_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492122136,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492121920,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226023216,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226022804,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285330008,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285328992,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272293384,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272291808,
      "name": "bpf_prog_inc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580775281,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774240,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580721457,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720416,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580766529,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765488,
      "name": "bpf_prog_inc",
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
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824689,
      "name": "bpf_prog_inc",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1480",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__bpf_prog_get"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/events/core.c:perf_event_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823648,
      "name": "bpf_prog_inc",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_prog_inc(struct bpf_prog * prog)
```
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
<b>Return type changed. </b>
<code>struct bpf_prog *</code> ➡️ <code>void</code>
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
