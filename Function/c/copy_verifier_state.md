# Function: <code>copy_verifier_state</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int copy_verifier_state(struct bpf_verifier_state * dst, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568496,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:355",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568496,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645024,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:457",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645024,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707872,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:702",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707872,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782112,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782112,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833040,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833040,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961504,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:843",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961504,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961440,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:869",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961440,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961200,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:918",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961200,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:930",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165424,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
    },
    {
      "addr": 18446744071592180813,
      "name": "copy_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1157",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445360,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071593954796,
      "name": "copy_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1359",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800592,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071596014401,
      "name": "copy_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1736",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985952,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071596535580,
      "name": "copy_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1389",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114688,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446744071597436948,
      "name": "copy_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492156520,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492156520,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226053308,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226053308,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285367536,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285367536,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272316538,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272316538,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801840,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801840,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748016,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748016,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793088,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793088,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int copy_verifier_state(struct bpf_verifier_state * dst_state, const struct bpf_verifier_state * src)
```

```json
{
  "name": "copy_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851472,
      "name": "copy_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851472,
      "name": "copy_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int copy_verifier_state(struct bpf_verifier_state * dst, const struct bpf_verifier_state * src)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_state * dst_state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_state * dst</code>
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
