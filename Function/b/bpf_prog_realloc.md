# Function: <code>bpf_prog_realloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580356912,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:101",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356912,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580412176,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:102",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412176,
      "name": "bpf_prog_realloc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460320,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460320,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478560,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:106",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478560,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537040,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537040,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620800,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:106",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620800,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680256,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:194",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680256,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748256,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748256,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798832,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798832,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916144,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:217",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_migrate_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916144,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912176,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:219",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_migrate_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912176,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915712,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:222",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915712,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118128,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:222",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118128,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386848,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:227",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386848,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735248,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:235",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735248,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894560,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:236",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894560,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018320,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:240",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018320,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492112400,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492112400,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226014160,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226014160,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285318880,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285318880,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272285588,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272285588,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767632,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767632,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713808,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713808,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758880,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758880,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
struct bpf_prog * bpf_prog_realloc(struct bpf_prog * fp_old, unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_realloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816976,
      "name": "bpf_prog_realloc",
      "external": true,
      "loc": "kernel/bpf/core.c:216",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816976,
      "name": "bpf_prog_realloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
