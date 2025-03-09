# Function: <code>audit_ctl_lock</code>

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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230415,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:245",
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
      "addr": 18446744071580218864,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282812,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:241",
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
      "addr": 18446744071580271312,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332876,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580322208,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381740,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580371008,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580458508,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:229",
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
      "addr": 18446744071580444848,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580446988,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:234",
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
      "addr": 18446744071580433344,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580451260,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:234",
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
      "addr": 18446744071580437232,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616246,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:234",
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
      "addr": 18446744071580601872,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821462,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:236",
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
      "addr": 18446744071580805696,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581107846,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:236",
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
      "addr": 18446744071581091360,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581199494,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:236",
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
      "addr": 18446744071581182960,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581305548,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:235",
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
      "addr": 18446744071581289136,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491647432,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446603336491635480,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225599456,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 3225588344,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284644592,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 13835058055284629648,
      "name": "audit_ctl_lock",
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272042226,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446743936272032046,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580350540,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580339808,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297708,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580286976,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580341788,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580331056,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
```

```json
{
  "name": "audit_ctl_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397068,
      "name": "audit_ctl_lock",
      "external": true,
      "loc": "kernel/audit.c:228",
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
      "addr": 18446744071580386336,
      "name": "audit_ctl_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void audit_ctl_lock()
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
