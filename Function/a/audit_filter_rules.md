# Function: <code>audit_filter_rules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int audit_filter_rules(struct task_struct * tsk, struct audit_krule * rule, struct audit_context * ctx, struct audit_names * name, enum audit_state * state, bool task_creation)
```

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052688,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_filter_syscall",
        "kernel/auditsc.c:audit_filter_inodes",
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052688,
      "name": "audit_filter_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3629
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085728,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:439",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_filter_inodes",
        "kernel/auditsc.c:audit_filter_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085728,
      "name": "audit_filter_rules.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3825
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580125984,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:439",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_filter_inodes",
        "kernel/auditsc.c:audit_filter_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125984,
      "name": "audit_filter_rules.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3880
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131664,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:440",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131664,
      "name": "audit_filter_rules.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3875
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184096,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:440",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184096,
      "name": "audit_filter_rules.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3902
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243920,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:444",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243920,
      "name": "audit_filter_rules.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580298112,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298112,
      "name": "audit_filter_rules.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580351104,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351104,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580399872,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399872,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3657
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580474992,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:449",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474992,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3459
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463136,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:465",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463136,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3526
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580466880,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:465",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466880,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3549
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:471",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633872,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3560
    },
    {
      "addr": 18446744071592162689,
      "name": "audit_filter_rules.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580841440,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:461",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_filter_syscall",
        "kernel/auditsc.c:audit_filter_uring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841440,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3549
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581128512,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:461",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:__audit_filter_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128512,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3549
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581218272,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:462",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:__audit_filter_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218272,
      "name": "audit_filter_rules.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3904
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581324720,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:464",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:__audit_filter_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324720,
      "name": "audit_filter_rules.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3680
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491662568,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491662568,
      "name": "audit_filter_rules.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2936
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225619224,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225619224,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284665184,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284665184,
      "name": "audit_filter_rules.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4532
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
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272054648,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272054648,
      "name": "audit_filter_rules.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2582
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368672,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368672,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315840,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315840,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359920,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359920,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_filter_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580415232,
      "name": "audit_filter_rules",
      "external": false,
      "loc": "kernel/auditsc.c:438",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415232,
      "name": "audit_filter_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3695
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int audit_filter_rules(struct task_struct * tsk, struct audit_krule * rule, struct audit_context * ctx, struct audit_names * name, enum audit_state * state, bool task_creation)
```
</details>
</li>
</ul>
