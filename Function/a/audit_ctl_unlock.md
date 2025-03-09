# Function: <code>audit_ctl_unlock</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230523,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:254",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218912,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282920,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:250",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271360,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332986,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322256,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381850,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371056,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580458618,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:238",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444896,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580447098,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:243",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433392,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580451370,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:243",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437280,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616282,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:243",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601920,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821498,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:245",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805744,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581107882,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:245",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091424,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581199530,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:245",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183024,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581305584,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:244",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289200,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491647544,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491635544,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225599584,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225588404,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284644732,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284629728,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272042336,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272032098,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580350650,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339856,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297818,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287024,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580341898,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331104,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void audit_ctl_unlock()
```

```json
{
  "name": "audit_ctl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397178,
      "name": "audit_ctl_unlock",
      "external": true,
      "loc": "kernel/audit.c:237",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:prune_tree_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386384,
      "name": "audit_ctl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void audit_ctl_unlock()
```
</details>
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
