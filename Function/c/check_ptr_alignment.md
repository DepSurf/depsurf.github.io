# Function: <code>check_ptr_alignment</code>

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
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580427177,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:712",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access"
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
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580478534,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:713",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access"
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
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580503755,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:850",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559664,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1054",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559664,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580654271,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1493",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access"
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
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580718206,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1746",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access"
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797520,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2526",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797520,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848624,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848624,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976992,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2875",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976992,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979952,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2959",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979952,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990976,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3499",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990976,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3574",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203584,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071592182972,
      "name": "check_ptr_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4125",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486416,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071593957035,
      "name": "check_ptr_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4580",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822928,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071596015689,
      "name": "check_ptr_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5505",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964224,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
    },
    {
      "addr": 18446744071596534807,
      "name": "check_ptr_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5720",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093968,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
    },
    {
      "addr": 18446744071597436107,
      "name": "check_ptr_alignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492173568,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492173568,
      "name": "check_ptr_alignment",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226070612,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226070612,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285387024,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285387024,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272329852,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272329852,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817424,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817424,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763600,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763600,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808672,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808672,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```

```json
{
  "name": "check_ptr_alignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580867056,
      "name": "check_ptr_alignment",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2527",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867056,
      "name": "check_ptr_alignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size, bool strict_alignment_once)
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
