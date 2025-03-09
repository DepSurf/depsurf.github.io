# Function: <code>is_state_visited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580370469,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1656",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580429369,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2183",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580481168,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2592",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507123,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3011",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574465,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3766",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580664633,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4615",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580734989,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5718",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811952,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7223",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811952,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2280
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580863088,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863088,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2339
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006544,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8371",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006544,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1581
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007936,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9159",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007936,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1594
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014576,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10323",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014576,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1736
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10654",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232176,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2672
    },
    {
      "addr": 18446744071592184317,
      "name": "is_state_visited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11710",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519120,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2697
    },
    {
      "addr": 18446744071593958516,
      "name": "is_state_visited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13708",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883104,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3424
    },
    {
      "addr": 18446744071596018612,
      "name": "is_state_visited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15860",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044880,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3285
    },
    {
      "addr": 18446744071596538777,
      "name": "is_state_visited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:16918",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160672,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4799
    },
    {
      "addr": 18446744071597439843,
      "name": "is_state_visited.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492188568,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492188568,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2560
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226084876,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226084876,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2636
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285404512,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285404512,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3172
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272341614,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272341614,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2132
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831888,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831888,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2339
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580778064,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778064,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2339
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823136,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823136,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2339
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "is_state_visited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881456,
      "name": "is_state_visited",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7238",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881456,
      "name": "is_state_visited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2339
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
int is_state_visited(struct bpf_verifier_env * env, int insn_idx)
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
