# Function: <code>bpf_check_uarg_tail_zero</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580631888,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:71",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631888,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580689264,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:70",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689264,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580757744,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757744,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580807664,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807664,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947786,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:73",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_btf_line",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935776,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945975,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:75",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932416,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580948313,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:76",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935424,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135472,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:76",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135472,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408240,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:80",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408240,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761088,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:80",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761088,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581922048,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:81",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922048,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int bpf_check_uarg_tail_zero(bpfptr_t uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048480,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:84",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048480,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492126560,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492126560,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226025924,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226025924,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285333376,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285333376,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272294914,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272294914,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580776464,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776464,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580722640,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722640,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580767712,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767712,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```

```json
{
  "name": "bpf_check_uarg_tail_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580825936,
      "name": "bpf_check_uarg_tail_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:62",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "net/bpf/test_run.c:bpf_ctx_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825936,
      "name": "bpf_check_uarg_tail_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bpf_check_uarg_tail_zero(void * uaddr, size_t expected_size, size_t actual_size)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * uaddr</code> ➡️ <code>bpfptr_t uaddr</code>
</li>
</ul>
</details>
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
