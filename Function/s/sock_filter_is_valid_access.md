# Function: <code>sock_filter_is_valid_access</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type * reg_type)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587014432,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:2845",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014432,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587141984,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:3180",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141984,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587647264,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:3677",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647264,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587949296,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:5238",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587949296,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588121264,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:5953",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121264,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588468592,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6635",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468592,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588674160,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674160,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589515248,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6936",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515248,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589520800,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7742",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589520800,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589419824,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7864",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419824,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590145440,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7994",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145440,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591699728,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8397",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591699728,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593491120,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8536",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593491120,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593955984,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8688",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593955984,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594739824,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8779",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594739824,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502226592,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502226592,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234972864,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234972864,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295714816,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295714816,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278471402,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278471402,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280896,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280896,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587993712,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993712,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588612720,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612720,
      "name": "sock_filter_is_valid_access",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "sock_filter_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588750400,
      "name": "sock_filter_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6722",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750400,
      "name": "sock_filter_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type * reg_type)
```
</details>
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
