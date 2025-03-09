# Function: <code>do_jit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347088,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347088,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6989
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
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579353456,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:350",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353456,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7069
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
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371280,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:350",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371280,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7069
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363968,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:354",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363968,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390640,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:356",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390640,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6552
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:411",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403872,
      "name": "do_jit.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6353
    },
    {
      "addr": 18446744071579411013,
      "name": "do_jit.isra.3.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:411",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435312,
      "name": "do_jit.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7499
    },
    {
      "addr": 18446744071579443624,
      "name": "do_jit.isra.3.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451088,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7848
    },
    {
      "addr": 18446744071579459763,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477152,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7834
    },
    {
      "addr": 18446744071579485811,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:655",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501200,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7664
    },
    {
      "addr": 18446744071579513165,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:792",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484864,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7651
    },
    {
      "addr": 18446744071591276262,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:898",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487024,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9093
    },
    {
      "addr": 18446744071591219065,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:896",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553856,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12349
    },
    {
      "addr": 18446744071592097376,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, u8 * rw_image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:894",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643744,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11865
    },
    {
      "addr": 18446744071593864628,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, u8 * rw_image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:966",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761840,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11944
    },
    {
      "addr": 18446744071595972962,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, u8 * rw_image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:966",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808256,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12335
    },
    {
      "addr": 18446744071596490566,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, u8 * rw_image, int oldproglen, struct jit_context * ctx, bool jmp_padding)
```

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:1140",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847248,
      "name": "do_jit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12948
    },
    {
      "addr": 18446744071597387422,
      "name": "do_jit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450816,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7834
    },
    {
      "addr": 18446744071579459475,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379792,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7834
    },
    {
      "addr": 18446744071579388451,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450736,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7834
    },
    {
      "addr": 18446744071579459395,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_jit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_jit",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:380",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482480,
      "name": "do_jit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7834
    },
    {
      "addr": 18446744071579491118,
      "name": "do_jit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_jit(struct bpf_prog * bpf_prog, int * addrs, u8 * image, int oldproglen, struct jit_context * ctx)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool jmp_padding</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * rw_image</code>
</li>
<li>
<b>Param reordered. </b>
<code>bpf_prog, addrs, image, oldproglen, ctx, jmp_padding</code> ➡️ <code>bpf_prog, addrs, image, rw_image, oldproglen, ctx, jmp_padding</code>
</li>
</ul>
</details>
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
