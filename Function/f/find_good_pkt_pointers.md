# Function: <code>find_good_pkt_pointers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580432044,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1613",
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
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477808,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1824",
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
      "addr": 18446744071580477808,
      "name": "find_good_pkt_pointers.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580501232,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2174",
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
      "addr": 18446744071580501232,
      "name": "find_good_pkt_pointers.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * state, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554048,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2550",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554048,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641280,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3337",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641280,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703152,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3942",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703152,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772448,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5101",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772448,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823360,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823360,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950576,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6182",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950576,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949184,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6786",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949184,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953104,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7949",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953104,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157952,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8242",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157952,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434592,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9230",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434592,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788384,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11149",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788384,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949552,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13072",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949552,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14063",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077232,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071597435075,
      "name": "find_good_pkt_pointers.cold",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492150344,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492150344,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226043004,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers",
        "kernel/bpf/verifier.c:try_match_pkt_pointers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226043004,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285359520,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285359520,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272311102,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272311102,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792160,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792160,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738336,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738336,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783408,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783408,
      "name": "find_good_pkt_pointers",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void find_good_pkt_pointers(struct bpf_verifier_state * vstate, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```

```json
{
  "name": "find_good_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841792,
      "name": "find_good_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5111",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841792,
      "name": "find_good_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void find_good_pkt_pointers(struct bpf_verifier_state * state, struct bpf_reg_state * dst_reg, enum bpf_reg_type type, bool range_right_open)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_state * vstate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_state * state</code>
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
