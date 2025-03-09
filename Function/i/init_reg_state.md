# Function: <code>init_reg_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580370361,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:472",
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
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580429256,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:478",
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
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580480928,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:447",
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
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580506905,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:476",
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
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574248,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:598",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647088,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:726",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647088,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709424,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:977",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709424,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580786688,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1041",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786688,
      "name": "init_reg_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837792,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837792,
      "name": "init_reg_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970048,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1354",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970048,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969488,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1399",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969488,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977344,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1491",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977344,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581227648,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1511",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227648,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513424,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1715",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513424,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875328,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875328,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582006976,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2328",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006976,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135584,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2334",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:push_callback_call",
        "kernel/bpf/verifier.c:setup_func_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135584,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492162928,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492162928,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226058672,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226058672,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285373680,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285373680,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272320560,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272320560,
      "name": "init_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806592,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806592,
      "name": "init_reg_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752768,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752768,
      "name": "init_reg_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797840,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797840,
      "name": "init_reg_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
```

```json
{
  "name": "init_reg_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856224,
      "name": "init_reg_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1042",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856224,
      "name": "init_reg_state",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void init_reg_state(struct bpf_verifier_env * env, struct bpf_func_state * state)
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
