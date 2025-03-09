# Function: <code>unfreeze_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579999554,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:329",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_apply_state"
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
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031826,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:329",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_apply_state"
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
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580066194,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:329",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_apply_state"
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
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580069447,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:329",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_apply_state"
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122064,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:329",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122064,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181728,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:329",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181728,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229760,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:329",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229760,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280592,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280592,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328784,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328784,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401296,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401296,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388544,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388544,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391472,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391472,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553552,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553552,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752320,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752320,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029936,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:322",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029936,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118304,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:327",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118304,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216544,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:333",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216544,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491589320,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491589320,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225550024,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284571216,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284571216,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271996430,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271996430,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297584,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297584,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244928,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244928,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288832,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288832,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void unfreeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "unfreeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342960,
      "name": "unfreeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:329",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342960,
      "name": "unfreeze_cgroup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void unfreeze_cgroup(struct freezer * freezer)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unfreeze_cgroup(struct freezer * freezer)
```
</details>
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
