# Function: <code>quota_state_to_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581420928,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:291",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstate",
        "fs/quota/quota.c:quota_getstatev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420928,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581602544,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:319",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602544,
      "name": "quota_state_to_flags.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581691040,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691040,
      "name": "quota_state_to_flags.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581745184,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745184,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581892256,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:316",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892256,
      "name": "quota_state_to_flags.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074768,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:317",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074768,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168864,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168864,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331744,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331744,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430928,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430928,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582727632,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:313",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727632,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582799728,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:333",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799728,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582827008,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:334",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827008,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583159056,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:334",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159056,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583649136,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:335",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649136,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584255024,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:335",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255024,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485616,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:335",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485616,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584708576,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:335",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708576,
      "name": "quota_state_to_flags.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494043744,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494043744,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227504332,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227504332,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287698240,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287698240,
      "name": "quota_state_to_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273547078,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273547078,
      "name": "quota_state_to_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399664,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399664,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582337360,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337360,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390144,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390144,
      "name": "quota_state_to_flags",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int quota_state_to_flags(struct qc_state * state)
```

```json
{
  "name": "quota_state_to_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469680,
      "name": "quota_state_to_flags",
      "external": false,
      "loc": "fs/quota/quota.c:315",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getstatev",
        "fs/quota/quota.c:quota_getstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469680,
      "name": "quota_state_to_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int quota_state_to_flags(struct qc_state * state)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int quota_state_to_flags(struct qc_state * state)
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
