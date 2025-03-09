# Function: <code>bpf_fd_array_map_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580386192,
      "name": "bpf_fd_array_map_clear",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:252",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_put_uref",
        "kernel/bpf/arraymap.c:perf_event_array_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386192,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580449395,
      "name": "bpf_fd_array_map_clear",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:397",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_put_uref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450288,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580506227,
      "name": "bpf_fd_array_map_clear",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:393",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_put_uref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507568,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536140,
      "name": "bpf_fd_array_map_clear",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:429",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_put_uref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537632,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580600300,
      "name": "bpf_fd_array_map_clear",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:474",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_put_uref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602064,
      "name": "bpf_fd_array_map_clear",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696024,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:529",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694480,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768920,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:548",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766896,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580853288,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850800,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580904328,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901840,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049930,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:664",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581063258,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:803",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581078394,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:845",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581306122,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:866",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581604699,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:897",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581987035,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:903",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582178507,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:927",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582326923,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:933",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free",
        "kernel/bpf/arraymap.c:perf_event_fd_array_map_free",
        "kernel/bpf/arraymap.c:prog_array_map_clear_deferred"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492234368,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492234368,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226130104,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226130104,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285455472,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285455472,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272379974,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272377360,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873128,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870640,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819256,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816768,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864376,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861888,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void bpf_fd_array_map_clear(struct bpf_map * map)
```

```json
{
  "name": "bpf_fd_array_map_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922904,
      "name": "bpf_fd_array_map_clear",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:596",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_of_map_free",
        "kernel/bpf/arraymap.c:cgroup_fd_array_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920368,
      "name": "bpf_fd_array_map_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map * map)
```
</details>
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
