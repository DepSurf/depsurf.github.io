# Function: <code>bpf_sock_is_valid_access</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588121269,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5941",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147808,
      "name": "bpf_sock_is_valid_access",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588468448,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6607",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468448,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588674016,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674016,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589539701,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6907",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_sock_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509072,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071589539760,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589548853,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7713",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_sock_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512736,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071589548912,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589446805,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7835",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589411792,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071589446864,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590181973,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7965",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138752,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071590182032,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591744405,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8360",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591692528,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071591744496,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593534021,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8499",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593484240,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071593534128,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594001877,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8651",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593950128,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071594001984,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594786197,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8742",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594732928,
      "name": "bpf_sock_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071594786304,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502226280,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502226280,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234972480,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234972480,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295714368,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295714368,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278471130,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278471130,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280752,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280752,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587993568,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993568,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588612576,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612576,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588750256,
      "name": "bpf_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "net/core/filter.c:bpf_sock_common_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750256,
      "name": "bpf_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```
</details>
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
