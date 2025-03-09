# Function: <code>audit_field_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053001,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:358",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_filter_rules"
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
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580086299,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:359",
      "file": "kernel/auditsc.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126389,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:359",
      "file": "kernel/auditsc.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580131993,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:360",
      "file": "kernel/auditsc.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580184413,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:360",
      "file": "kernel/auditsc.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580244314,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:360",
      "file": "kernel/auditsc.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580299589,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346880,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346880,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395648,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395648,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469648,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:365",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469648,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580457824,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:381",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457824,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461920,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:381",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461920,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628800,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:387",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628800,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834832,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:377",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834832,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121776,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:377",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121776,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213456,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:378",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213456,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319456,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:380",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319456,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491661904,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491661904,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225611132,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225611132,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284664160,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284664160,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272054024,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272054024,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364448,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364448,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311616,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311616,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355696,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355696,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```

```json
{
  "name": "audit_field_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411008,
      "name": "audit_field_compare",
      "external": false,
      "loc": "kernel/auditsc.c:354",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411008,
      "name": "audit_field_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int audit_field_compare(struct task_struct * tsk, const struct cred * cred, struct audit_field * f, struct audit_context * ctx, struct audit_names * name)
```
</details>
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
