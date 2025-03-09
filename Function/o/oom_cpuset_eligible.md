# Function: <code>oom_cpuset_eligible</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053680,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053680,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109696,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109696,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292816,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:86",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292816,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336976,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:88",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336976,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581355648,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:88",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355648,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581603488,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:89",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603488,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963744,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:89",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_evaluate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963744,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582397776,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:89",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_evaluate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397776,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603680,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:89",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_evaluate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603680,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582775136,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:89",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_evaluate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775136,
      "name": "oom_cpuset_eligible.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492474560,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492474560,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:120",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285760736,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285760736,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:120",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078544,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078544,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025728,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025728,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069744,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069744,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```

```json
{
  "name": "oom_cpuset_eligible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131280,
      "name": "oom_cpuset_eligible",
      "external": false,
      "loc": "mm/oom_kill.c:85",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131280,
      "name": "oom_cpuset_eligible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool oom_cpuset_eligible(struct task_struct * start, struct oom_control * oc)
```
</details>
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
