# Function: <code>push_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368528,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1438",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368528,
      "name": "push_insn.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580426752,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1903",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426752,
      "name": "push_insn.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478112,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2296",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478112,
      "name": "push_insn.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503344,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2705",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503344,
      "name": "push_insn.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562304,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3307",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562304,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646304,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4124",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646304,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734304,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4836",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734304,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811520,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6222",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811520,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862656,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862656,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003424,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7363",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg",
        "kernel/bpf/verifier.c:check_cfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003424,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006496,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8099",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006496,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013024,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9263",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013024,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9578",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230576,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071592184297,
      "name": "push_insn.cold",
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10560",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517440,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071593958495,
      "name": "push_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12536",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881376,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071596018591,
      "name": "push_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14496",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974992,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071596535068,
      "name": "push_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15439",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn",
        "kernel/bpf/verifier.c:visit_func_call_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090336,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
    },
    {
      "addr": 18446744071597435688,
      "name": "push_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492188080,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492188080,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226084444,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226084444,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285403856,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285403856,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272341226,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272341226,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831456,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831456,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777632,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777632,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822704,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822704,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env, bool loop_ok)
```

```json
{
  "name": "push_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881024,
      "name": "push_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881024,
      "name": "push_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int push_insn(int t, int w, int e, struct bpf_verifier_env * env)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool loop_ok</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool loop_ok</code>
</li>
</ul>
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
