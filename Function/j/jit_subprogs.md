# Function: <code>jit_subprogs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580677900,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5418",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580745349,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6633",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809712,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8658",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809712,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860848,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860848,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988768,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988768,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997488,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10727",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997488,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2082
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004704,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12011",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004704,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2132
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12398",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220064,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2334
    },
    {
      "addr": 18446744071592183978,
      "name": "jit_subprogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13458",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505296,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2548
    },
    {
      "addr": 18446744071593958247,
      "name": "jit_subprogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15443",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860144,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2523
    },
    {
      "addr": 18446744071596017612,
      "name": "jit_subprogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17654",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032576,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2559
    },
    {
      "addr": 18446744071596537867,
      "name": "jit_subprogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18821",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174624,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2845
    },
    {
      "addr": 18446744071597441523,
      "name": "jit_subprogs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492186224,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492186224,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226082556,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226082556,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285401712,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285401712,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272339690,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272339690,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829648,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829648,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580775824,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775824,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820896,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820896,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int jit_subprogs(struct bpf_verifier_env * env)
```

```json
{
  "name": "jit_subprogs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879280,
      "name": "jit_subprogs",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879280,
      "name": "jit_subprogs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1359
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
int jit_subprogs(struct bpf_verifier_env * env)
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
