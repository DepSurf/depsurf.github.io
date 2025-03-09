# Function: <code>flow_dissector_is_valid_access</code>

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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588116336,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6353",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116336,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588435424,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7068",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435424,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641296,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641296,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589508528,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7382",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508528,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589512096,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8202",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512096,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589410992,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8324",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410992,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590138160,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8454",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138160,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591691728,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8867",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591691728,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593482128,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:9055",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593482128,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593947504,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:9198",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593947504,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594730288,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:9289",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594730288,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502185816,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502185816,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234933660,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234933660,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295664704,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295664704,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278442020,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278442020,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588248032,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248032,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587960848,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960848,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588579856,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579856,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "flow_dissector_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588717344,
      "name": "flow_dissector_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7155",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717344,
      "name": "flow_dissector_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bool flow_dissector_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
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
