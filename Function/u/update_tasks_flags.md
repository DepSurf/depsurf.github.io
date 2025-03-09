# Function: <code>update_tasks_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580008730,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cpuset.c:1293",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:update_flag"
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
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580041246,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cpuset.c:1295",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:update_flag"
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
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580077893,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cpuset.c:1295",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:update_flag"
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
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580082591,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1283",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:update_flag"
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129200,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129200,
      "name": "update_tasks_flags",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188560,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1294",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188560,
      "name": "update_tasks_flags",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236656,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1817",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236656,
      "name": "update_tasks_flags",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287168,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1778",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287168,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580335504,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580335504,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408880,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1854",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408880,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580396160,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1877",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396160,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580399104,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1877",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399104,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580561744,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1928",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580561744,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759472,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1968",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759472,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041040,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2157",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041040,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128944,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2192",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128944,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228096,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2973",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228096,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491601864,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491601864,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225562676,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:update_flag"
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284583872,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284583872,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272002294,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272002294,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580304304,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580304304,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251648,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251648,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295552,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295552,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_tasks_flags(struct cpuset * cs)
```

```json
{
  "name": "update_tasks_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580350208,
      "name": "update_tasks_flags",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1852",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_flag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350208,
      "name": "update_tasks_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_tasks_flags(struct cpuset * cs)
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
void update_tasks_flags(struct cpuset * cs)
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
