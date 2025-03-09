# Function: <code>rcu_test_sync_prims</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:825",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_runtime_mode",
        "kernel/rcu/tree.c:rcu_exp_runtime_mode",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830272,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:200",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830112,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:201",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870112,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:201",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904160,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:201",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951792,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990448,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:189",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990448,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040592,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040592,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:229",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095184,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:217",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077504,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:219",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078944,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:219",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214176,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:219",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372992,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:219",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598352,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:257",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671856,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:258",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738704,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491241664,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225254232,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284143088,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284143088,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271770632,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009328,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009328,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948112,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948112,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580000864,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000864,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_test_sync_prims()
```

```json
{
  "name": "rcu_test_sync_prims",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047792,
      "name": "rcu_test_sync_prims",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_scheduler_starting",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047792,
      "name": "rcu_test_sync_prims",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void rcu_test_sync_prims()
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
