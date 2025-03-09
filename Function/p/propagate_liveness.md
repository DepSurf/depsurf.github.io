# Function: <code>propagate_liveness</code>

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
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580576205,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3756",
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
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580668978,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4575",
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
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580740900,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5676",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580813435,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7120",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580864627,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970368,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8268",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970368,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969808,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9056",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969808,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969984,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10220",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969984,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179728,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10551",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179728,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458560,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11607",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458560,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820832,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13603",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820832,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978096,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15652",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978096,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106384,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:16710",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106384,
      "name": "propagate_liveness",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492190200,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226086584,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285406704,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272343028,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580833427,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580779603,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580824675,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580882995,
      "name": "propagate_liveness",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7135",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:is_state_visited"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int propagate_liveness(struct bpf_verifier_env * env, const struct bpf_verifier_state * vstate, struct bpf_verifier_state * vparent)
```
</details>
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
