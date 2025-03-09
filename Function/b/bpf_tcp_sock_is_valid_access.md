# Function: <code>bpf_tcp_sock_is_valid_access</code>

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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466768,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5544",
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
      "addr": 18446744071588466768,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588672336,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446744071588672336,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589538016,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5678",
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
      "addr": 18446744071589538016,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589547152,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6230",
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
      "addr": 18446744071589547152,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589445104,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6332",
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
      "addr": 18446744071589445104,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590180272,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6456",
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
      "addr": 18446744071590180272,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591742800,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6786",
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
      "addr": 18446744071591742800,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593532336,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6798",
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
      "addr": 18446744071593532336,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594000064,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:6955",
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
      "addr": 18446744071594000064,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594784384,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:7045",
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
      "addr": 18446744071594784384,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502225080,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446603336502225080,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234970912,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 3234970912,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295712720,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 13835058055295712720,
      "name": "bpf_tcp_sock_is_valid_access",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278469656,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446743936278469656,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588279072,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446744071588279072,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991888,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446744071587991888,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588610896,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446744071588610896,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_tcp_sock_is_valid_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748576,
      "name": "bpf_tcp_sock_is_valid_access",
      "external": true,
      "loc": "net/core/filter.c:5552",
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
      "addr": 18446744071588748576,
      "name": "bpf_tcp_sock_is_valid_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool bpf_tcp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
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
