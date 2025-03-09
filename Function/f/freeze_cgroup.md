# Function: <code>freeze_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579999511,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:318",
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
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031783,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:318",
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
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580066151,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup_freezer.c:318",
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
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580069404,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:318",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121968,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:318",
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
      "addr": 18446744071580121968,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181632,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:318",
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
      "addr": 18446744071580181632,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229664,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:318",
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
      "addr": 18446744071580229664,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280496,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580280496,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328672,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580328672,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401200,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580401200,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388448,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580388448,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391376,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580391376,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553456,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580553456,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752176,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580752176,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029776,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:311",
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
      "addr": 18446744071581029776,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118144,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:316",
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
      "addr": 18446744071581118144,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216384,
      "name": "freeze_cgroup",
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
      "addr": 18446744071581216384,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491589200,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491589200,
      "name": "freeze_cgroup",
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
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225549880,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284571056,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284571056,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271996346,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271996346,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297472,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580297472,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244816,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580244816,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288720,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580288720,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
```

```json
{
  "name": "freeze_cgroup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342848,
      "name": "freeze_cgroup",
      "external": false,
      "loc": "kernel/cgroup/legacy_freezer.c:318",
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
      "addr": 18446744071580342848,
      "name": "freeze_cgroup",
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
void freeze_cgroup(struct freezer * freezer)
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
void freeze_cgroup(struct freezer * freezer)
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
