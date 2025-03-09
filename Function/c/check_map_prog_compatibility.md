# Function: <code>check_map_prog_compatibility</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493347,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2916",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580521422,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3344",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582730,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4147",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580675028,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5034",
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743831,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6199",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580783782,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7843",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580834726,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963760,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8968",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963760,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966912,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9845",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966912,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974912,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11089",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974912,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11436",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186048,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071592181479,
      "name": "check_map_prog_compatibility.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12492",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471536,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    },
    {
      "addr": 18446744071593956213,
      "name": "check_map_prog_compatibility.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14495",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831344,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071596015930,
      "name": "check_map_prog_compatibility.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:16711",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003280,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071596536628,
      "name": "check_map_prog_compatibility.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
```

```json
{
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17867",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133088,
      "name": "check_map_prog_compatibility",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071597437982,
      "name": "check_map_prog_compatibility.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492158724,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226055168,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285369672,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272317996,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580803526,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580749702,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580794774,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
  "name": "check_map_prog_compatibility",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853158,
      "name": "check_map_prog_compatibility",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7858",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:replace_map_fd_with_map_ptr"
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
int check_map_prog_compatibility(struct bpf_verifier_env * env, struct bpf_map * map, struct bpf_prog * prog)
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
