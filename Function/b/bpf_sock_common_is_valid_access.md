# Function: <code>bpf_sock_common_is_valid_access</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588468560,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6595",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468560,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674128,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674128,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589539696,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6895",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_sock_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589539696,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548848,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7701",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_sock_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548848,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446800,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7823",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446800,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590181968,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7953",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181968,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591744400,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8348",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591744400,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593534016,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8487",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593534016,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594001872,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8639",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594001872,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594786192,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:8730",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594786192,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502226480,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502226480,
      "name": "bpf_sock_common_is_valid_access",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234972816,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234972816,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295714752,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295714752,
      "name": "bpf_sock_common_is_valid_access",
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278471308,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278471308,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588280864,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280864,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587993680,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993680,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588612688,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612688,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_sock_common_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588750368,
      "name": "bpf_sock_common_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6682",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750368,
      "name": "bpf_sock_common_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool bpf_sock_common_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```
</details>
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
