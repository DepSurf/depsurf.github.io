# Function: <code>bpf_patch_insn_single</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412400,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:166",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412400,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461152,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:248",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461152,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479376,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:251",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479376,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537856,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:247",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537856,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621664,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:295",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621664,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681120,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:403",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681120,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749136,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749136,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799712,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799712,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916992,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916992,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912944,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:428",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912944,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916512,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:434",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916512,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118960,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:434",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118960,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387792,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:446",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387792,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736240,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:454",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736240,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895632,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:455",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895632,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019392,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:472",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019392,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492113456,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492113456,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226015024,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226015024,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285320112,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285320112,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272286458,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272286458,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768512,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768512,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714688,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714688,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759760,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759760,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817856,
      "name": "bpf_patch_insn_single",
      "external": true,
      "loc": "kernel/bpf/core.c:432",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817856,
      "name": "bpf_patch_insn_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_single(struct bpf_prog * prog, u32 off, const struct bpf_insn * patch, u32 len)
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
