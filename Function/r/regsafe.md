# Function: <code>regsafe</code>

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
bool regsafe(struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct idpair * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580566960,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3502",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566960,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
bool regsafe(struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct idpair * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580643504,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4331",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643504,
      "name": "regsafe",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool regsafe(struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct idpair * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705856,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5409",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705856,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580777600,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6811",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777600,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580828528,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828528,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580957644,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7959",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:func_states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:func_states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956864,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580957532,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8747",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:func_states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:func_states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953680,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580956848,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9918",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956848,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581167949,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10249",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167088,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
    },
    {
      "addr": 18446744071592180833,
      "name": "regsafe.part.0.cold",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool regsafe(struct bpf_verifier_env * env, struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct bpf_id_pair * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11306",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:states_equal",
        "kernel/bpf/verifier.c:states_equal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447232,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071593954816,
      "name": "regsafe.cold",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool regsafe(struct bpf_verifier_env * env, struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct bpf_id_pair * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13278",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:func_states_equal",
        "kernel/bpf/verifier.c:func_states_equal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807840,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071596014531,
      "name": "regsafe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool regsafe(struct bpf_verifier_env * env, struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct bpf_idmap * idmap)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15288",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988336,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071596535667,
      "name": "regsafe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
bool regsafe(struct bpf_verifier_env * env, struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct bpf_idmap * idmap, bool exact)
```

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:16329",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:states_equal",
        "kernel/bpf/verifier.c:stacksafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118128,
      "name": "regsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
    },
    {
      "addr": 18446744071597437008,
      "name": "regsafe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492152784,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492152784,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226048608,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226048608,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285362688,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285362688,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272313508,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272313508,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580797328,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797328,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580743504,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743504,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788576,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788576,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regsafe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580846960,
      "name": "regsafe",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6826",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846960,
      "name": "regsafe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
bool regsafe(struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct idpair * idmap)
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
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
bool regsafe(struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct idpair * idmap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool regsafe(struct bpf_verifier_env * env, struct bpf_reg_state * rold, struct bpf_reg_state * rcur, struct bpf_id_pair * idmap)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_id_pair * idmap</code> ➡️ <code>struct bpf_idmap * idmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact</code>
</li>
</ul>
</details>
</li>
</ul>
