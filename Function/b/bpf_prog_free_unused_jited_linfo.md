# Function: <code>bpf_prog_free_unused_jited_linfo</code>

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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679968,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:129",
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
      "addr": 18446744071580679968,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747984,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580747984,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798560,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580798560,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922339,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:152",
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
      "addr": 18446744071580915840,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918687,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:154",
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
      "addr": 18446744071580911872,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492112072,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446603336492112072,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226013876,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 3226013876,
      "name": "bpf_prog_free_unused_jited_linfo",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285318448,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 13835058055285318448,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272285308,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446743936272285308,
      "name": "bpf_prog_free_unused_jited_linfo",
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767360,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580767360,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713536,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580713536,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758608,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580758608,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_free_unused_jited_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816704,
      "name": "bpf_prog_free_unused_jited_linfo",
      "external": true,
      "loc": "kernel/bpf/core.c:151",
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
      "addr": 18446744071580816704,
      "name": "bpf_prog_free_unused_jited_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void bpf_prog_free_unused_jited_linfo(struct bpf_prog * prog)
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
