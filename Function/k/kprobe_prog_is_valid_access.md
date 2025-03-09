# Function: <code>kprobe_prog_is_valid_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314496,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:302",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314496,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type * reg_type)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368240,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:428",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368240,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type * reg_type)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415296,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:453",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415296,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580429552,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:519",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429552,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580485504,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:565",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485504,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571216,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:598",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571216,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628848,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:634",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628848,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580689584,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:739",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689584,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580736544,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736544,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580850496,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1162",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850496,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580839232,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1391",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839232,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844000,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1085",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844000,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581043808,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1162",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043808,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581299312,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1340",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299312,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581624480,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1554",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624480,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764032,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1563",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764032,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882768,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1668",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882768,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492043432,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492043432,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225946036,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225946036,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285217200,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285217200,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705344,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705344,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651552,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651552,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696592,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696592,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "kprobe_prog_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580752112,
      "name": "kprobe_prog_is_valid_access",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:763",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752112,
      "name": "kprobe_prog_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_reg_type * reg_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_insn_access_aux * info</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_reg_type * reg_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog * prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>off, size, type, info</code> ➡️ <code>off, size, type, prog, info</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool kprobe_prog_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```
</details>
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
