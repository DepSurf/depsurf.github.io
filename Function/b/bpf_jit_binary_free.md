# Function: <code>bpf_jit_binary_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357536,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:172",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357536,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412896,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:242",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412896,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461648,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:324",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461648,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480892,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:523",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480800,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539372,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:532",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539280,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580623240,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:611",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623152,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682848,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:790",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682848,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751264,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751264,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801824,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801824,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919501,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:891",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919376,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915629,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:888",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915504,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919376,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:894",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919248,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121888,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:896",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121760,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391065,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1072",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390880,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740281,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1046",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740064,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899753,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1047",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899536,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023993,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1090",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023776,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492116444,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492116272,
      "name": "bpf_jit_binary_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226017692,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile",
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226017692,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285323956,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285323776,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272288934,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free"
      ],
      "caller_func": [
        "arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272288804,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770624,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770624,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716800,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716800,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761872,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761872,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_jit_binary_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_jit_binary_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820016,
      "name": "bpf_jit_binary_free",
      "external": true,
      "loc": "kernel/bpf/core.c:832",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820016,
      "name": "bpf_jit_binary_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
