# Function: <code>tnum_arshift</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683424,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:46",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683424,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754336,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:46",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754336,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838144,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838144,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889168,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889168,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029056,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029056,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036384,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036384,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049776,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049776,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186103,
      "name": "tnum_arshift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071581274480,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960380,
      "name": "tnum_arshift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581567920,
      "name": "tnum_arshift",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596020873,
      "name": "tnum_arshift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581943808,
      "name": "tnum_arshift",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596542499,
      "name": "tnum_arshift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071582129296,
      "name": "tnum_arshift",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597445429,
      "name": "tnum_arshift.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071582270880,
      "name": "tnum_arshift",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492215440,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492215440,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226112656,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226112656,
      "name": "tnum_arshift",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285436800,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285436800,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272363452,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272363452,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857968,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857968,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804096,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804096,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849216,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849216,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift, u8 insn_bitness)
```

```json
{
  "name": "tnum_arshift",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907536,
      "name": "tnum_arshift",
      "external": true,
      "loc": "kernel/bpf/tnum.c:47",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907536,
      "name": "tnum_arshift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct tnum tnum_arshift(struct tnum a, u8 min_shift)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 insn_bitness</code>
</li>
</ul>
</details>
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
