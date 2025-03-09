# Function: <code>fixup_bpf_calls</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580365324,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/syscall.c:452",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
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
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580422460,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/syscall.c:549",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
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
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580472909,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/syscall.c:590",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502688,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3643",
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
      "addr": 18446744071580502688,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580561248,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4470",
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
      "addr": 18446744071580561248,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672912,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5609",
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
      "addr": 18446744071580672912,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1618
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731872,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6840",
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
      "addr": 18446744071580731872,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2060
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807728,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8869",
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
      "addr": 18446744071580807728,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1984
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858880,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446744071580858880,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986208,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10016",
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
      "addr": 18446744071580986208,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2552
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994880,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11000",
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
      "addr": 18446744071580994880,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2604
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492184360,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446603336492184360,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1860
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226081036,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 3226081036,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1520
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285399424,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 13835058055285399424,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2284
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272338188,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446743936272338188,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1502
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827680,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446744071580827680,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773856,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446744071580773856,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818928,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446744071580818928,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
int fixup_bpf_calls(struct bpf_verifier_env * env)
```

```json
{
  "name": "fixup_bpf_calls",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877312,
      "name": "fixup_bpf_calls",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8884",
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
      "addr": 18446744071580877312,
      "name": "fixup_bpf_calls",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int fixup_bpf_calls(struct bpf_verifier_env * env)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int fixup_bpf_calls(struct bpf_verifier_env * env)
```
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
