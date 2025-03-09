# Function: <code>tnum_cast</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588384,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:134",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588384,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683824,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:144",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683824,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754736,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:144",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754736,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838544,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:145",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838544,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889584,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889584,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029701,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029472,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037029,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036800,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050421,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050192,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275189,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:153",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186225,
      "name": "tnum_cast.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581274928,
      "name": "tnum_cast",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568789,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:153",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960506,
      "name": "tnum_cast.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581568480,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944869,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:153",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596020999,
      "name": "tnum_cast.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071581944496,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582130357,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:153",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596542612,
      "name": "tnum_cast.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582129984,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272053,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:153",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_with_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597445542,
      "name": "tnum_cast.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582271568,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492216184,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492216184,
      "name": "tnum_cast",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226113952,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226113952,
      "name": "tnum_cast",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285437264,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285437264,
      "name": "tnum_cast",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272364164,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272364164,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858384,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858384,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804512,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804512,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849632,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849632,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
```

```json
{
  "name": "tnum_cast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907952,
      "name": "tnum_cast",
      "external": true,
      "loc": "kernel/bpf/tnum.c:150",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:coerce_reg_to_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907952,
      "name": "tnum_cast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_cast(struct tnum a, u8 size)
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
