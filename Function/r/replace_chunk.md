# Function: <code>replace_chunk</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314336,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314336,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366432,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366432,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415184,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415184,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494560,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:untag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494560,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482640,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_chunk",
        "kernel/audit_tree.c:untag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482640,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486528,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486528,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654176,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654176,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580863408,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863408,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151536,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151536,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244880,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244880,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351136,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:293",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:tag_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351136,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491680912,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491680912,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225634896,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225634896,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284691872,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284691872,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272070478,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272070478,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383984,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383984,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331152,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331152,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375232,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375232,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```

```json
{
  "name": "replace_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431360,
      "name": "replace_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:295",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431360,
      "name": "replace_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void replace_chunk(struct audit_chunk * new, struct audit_chunk * old)
```
</details>
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
