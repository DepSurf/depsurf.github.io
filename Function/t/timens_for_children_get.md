# Function: <code>timens_for_children_get</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261872,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:262",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261872,
      "name": "timens_for_children_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245456,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:259",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245456,
      "name": "timens_for_children_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250080,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:259",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250080,
      "name": "timens_for_children_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401200,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:259",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401200,
      "name": "timens_for_children_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622686,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:259",
      "file": "kernel/time/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620272,
      "name": "timens_for_children_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580888462,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:277",
      "file": "kernel/time/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885792,
      "name": "timens_for_children_get",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972302,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:277",
      "file": "kernel/time/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969648,
      "name": "timens_for_children_get",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
```

```json
{
  "name": "timens_for_children_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581067038,
      "name": "timens_for_children_get",
      "external": false,
      "loc": "kernel/time/namespace.c:277",
      "file": "kernel/time/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset",
        "kernel/time/namespace.c:proc_timens_show_offsets"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064384,
      "name": "timens_for_children_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct ns_common * timens_for_children_get(struct task_struct * task)
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
