# Function: <code>update_if_frozen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579999976,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:244",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read"
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
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032325,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:244",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read"
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
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580066693,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:244",
      "file": "kernel/cgroup_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read"
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
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580070059,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:244",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_read"
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122272,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:244",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122272,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181936,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:244",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181936,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229968,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:244",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229968,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280800,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280800,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329008,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329008,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401504,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401504,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388752,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388752,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391680,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391680,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553760,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553760,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752624,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752624,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030336,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:245",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030336,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118704,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:250",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118704,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216944,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:256",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216944,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491589440,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491589440,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225550636,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284571376,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284571376,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271996514,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271996514,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297808,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297808,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245152,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245152,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289056,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289056,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void update_if_frozen(struct cgroup_subsys_state * css)
```

```json
{
  "name": "update_if_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343184,
      "name": "update_if_frozen",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:244",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343184,
      "name": "update_if_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void update_if_frozen(struct cgroup_subsys_state * css)
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
void update_if_frozen(struct cgroup_subsys_state * css)
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
