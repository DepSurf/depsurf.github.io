# Function: <code>free_verifier_state</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582418,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:344",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:pop_stack"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643408,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:429",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643408,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705248,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:670",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705248,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777488,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777488,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828416,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828416,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955728,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:810",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955728,
      "name": "free_verifier_state",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956624,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:836",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956624,
      "name": "free_verifier_state",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959120,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:885",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959120,
      "name": "free_verifier_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164720,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:901",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164720,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444720,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1128",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444720,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800080,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1330",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800080,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983184,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1707",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983184,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111776,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1360",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_callback_call",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111776,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492151960,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492151960,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226048496,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226048496,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285361376,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285361376,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272312358,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272312358,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797216,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797216,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743392,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743392,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788464,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788464,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```

```json
{
  "name": "free_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846848,
      "name": "free_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:683",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_stack",
        "kernel/bpf/verifier.c:pop_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846848,
      "name": "free_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void free_verifier_state(struct bpf_verifier_state * state, bool free_self)
```
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
