# Function: <code>bpf_prog_inc_not_zero</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493637,
      "name": "bpf_prog_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:873",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543792,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1042",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543792,
      "name": "bpf_prog_inc_not_zero",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629936,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1143",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_fd_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629936,
      "name": "bpf_prog_inc_not_zero",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688560,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1329",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688560,
      "name": "bpf_prog_inc_not_zero",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756016,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1466",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756016,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812960,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812960,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923072,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1870",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923072,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919328,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1844",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919328,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923264,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1852",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923264,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125872,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1946",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125872,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397072,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2192",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397072,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747376,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2226",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747376,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907344,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2305",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907344,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031584,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2345",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031584,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492139576,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492139576,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226032220,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226032220,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285341216,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285341216,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272299754,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299754,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781760,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781760,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727936,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727936,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773008,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773008,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831232,
      "name": "bpf_prog_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1487",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831232,
      "name": "bpf_prog_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_prog_inc_not_zero(struct bpf_prog * prog)
```
</details>
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
