# Function: <code>cond_synchronize_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788128,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3359",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813056,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3357",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848208,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851568,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3377",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851568,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892016,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3360",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892016,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923168,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3166",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923168,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972000,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3005",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972000,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011840,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011840,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056288,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056288,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122096,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3469",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122096,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103760,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3779",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103760,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104016,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3887",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104016,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243264,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3858",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243264,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580414128,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3954",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414128,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640494,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3808",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644464,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580716288,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3808",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716288,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580790128,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3880",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790128,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491270272,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491270272,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225274528,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225274528,
      "name": "cond_synchronize_rcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284170208,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284170208,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271787680,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271787680,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025024,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025024,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966144,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966144,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016560,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016560,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void cond_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "cond_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064208,
      "name": "cond_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2774",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064208,
      "name": "cond_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void cond_synchronize_rcu(long unsigned int oldstate)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
