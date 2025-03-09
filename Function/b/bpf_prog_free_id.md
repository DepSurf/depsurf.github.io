# Function: <code>bpf_prog_free_id</code>

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
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580490420,
      "name": "bpf_prog_free_id",
      "external": false,
      "loc": "kernel/bpf/syscall.c:748",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580543529,
      "name": "bpf_prog_free_id",
      "external": false,
      "loc": "kernel/bpf/syscall.c:908",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580629616,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1002",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629616,
      "name": "bpf_prog_free_id.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580637920,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688176,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1185",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688176,
      "name": "bpf_prog_free_id.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580694272,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755616,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1291",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755616,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580765776,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806240,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806240,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580816736,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941504,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1690",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941504,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938208,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1658",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938208,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580940912,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1659",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940912,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144848,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1727",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144848,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419872,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1971",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419872,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void bpf_prog_free_id(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755161,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2004",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776784,
      "name": "bpf_prog_free_id",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581915689,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2082",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938944,
      "name": "bpf_prog_free_id",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582041561,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2122",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065552,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492138976,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492138976,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226022924,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226022924,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3226036144,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285329504,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285329504,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 13835058055285346448,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272293094,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272293094,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446743936272302808,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580775040,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775040,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580785536,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580721216,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721216,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580731712,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580766288,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766288,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580776784,
      "name": "bpf_prog_free_id",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "bpf_prog_free_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824448,
      "name": "bpf_prog_free_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1304",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:__bpf_prog_offload_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824448,
      "name": "bpf_prog_free_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580835056,
      "name": "bpf_prog_free_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_prog_free_id(struct bpf_prog * prog, bool do_idr_lock)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_idr_lock</code>
</li>
</ul>
</details>
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
