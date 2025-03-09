# Function: <code>prune_tree_chunks</code>

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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315200,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:570",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315200,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367424,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367424,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416176,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416176,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496736,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496736,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484816,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484816,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580487648,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487648,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655296,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655296,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864592,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864592,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152752,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152752,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246176,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246176,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352432,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:569",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352432,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491681440,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491681440,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225635996,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225635996,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284694192,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284694192,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272071132,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272071132,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384976,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384976,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332144,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332144,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376224,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376224,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
```

```json
{
  "name": "prune_tree_chunks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431760,
      "name": "prune_tree_chunks",
      "external": false,
      "loc": "kernel/audit_tree.c:571",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431760,
      "name": "prune_tree_chunks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
void prune_tree_chunks(struct audit_tree * victim, bool tagged)
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
