# Function: <code>bpf_prog_alloc_jited_linfo</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679824,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:109",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679824,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747840,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747840,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798416,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798416,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922254,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:132",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915680,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918603,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:134",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911712,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915360,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:143",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915360,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117776,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:143",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117776,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386448,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:148",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386448,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734800,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:156",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734800,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894112,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:157",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894112,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017872,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:161",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017872,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492111920,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492111920,
      "name": "bpf_prog_alloc_jited_linfo",
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226013708,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226013708,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285318192,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285318192,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272285168,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272285168,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767216,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767216,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713392,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713392,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758464,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758464,
      "name": "bpf_prog_alloc_jited_linfo",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_alloc_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816560,
      "name": "bpf_prog_alloc_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:131",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816560,
      "name": "bpf_prog_alloc_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int bpf_prog_alloc_jited_linfo(struct bpf_prog * prog)
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
