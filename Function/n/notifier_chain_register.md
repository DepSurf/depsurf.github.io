# Function: <code>notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579505743,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register"
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
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579519996,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543644,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530204,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556700,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584965,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579622165,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:21",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646960,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646960,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684096,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684096,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724080,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724080,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702320,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702320,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709456,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709456,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788405,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n, bool unique_priority)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895429,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio"
      ],
      "caller_func": [
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894192,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n, bool unique_priority)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046773,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio"
      ],
      "caller_func": [
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045392,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n, bool unique_priority)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099600,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:25",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099600,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n, bool unique_priority)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144416,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:25",
      "file": "kernel/notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register_unique_prio",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register_unique_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144416,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490859392,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490859392,
      "name": "notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224879040,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224879040,
      "name": "notifier_chain_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283689168,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283689168,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271517640,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271517640,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660416,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660416,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588768,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588768,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657680,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657680,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```

```json
{
  "name": "notifier_chain_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691392,
      "name": "notifier_chain_register",
      "external": false,
      "loc": "kernel/notifier.c:22",
      "file": "kernel/notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:srcu_notifier_chain_register",
        "kernel/notifier.c:raw_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:blocking_notifier_chain_register",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691392,
      "name": "notifier_chain_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int notifier_chain_register(struct notifier_block * * nl, struct notifier_block * n, bool unique_priority)
```
</details>
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
