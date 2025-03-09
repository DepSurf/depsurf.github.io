# Function: <code>rb_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580191743,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2537",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_write"
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
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580230745,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2531",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257520,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257520,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273952,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2502",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273952,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327104,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2498",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327104,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388384,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2577",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388384,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442848,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2625",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442848,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497008,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2602",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497008,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545184,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545184,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635056,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2672",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635056,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624832,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2965",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624832,
      "name": "rb_commit.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580627360,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3048",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627360,
      "name": "rb_commit.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809805,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3048",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799104,
      "name": "rb_commit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035908,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3091",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021936,
      "name": "rb_commit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322992,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3179",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322992,
      "name": "rb_commit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071581323360,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417728,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3183",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417728,
      "name": "rb_commit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071581418096,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525840,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3003",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525840,
      "name": "rb_commit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071581526208,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491837384,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491837384,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225778004,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225778004,
      "name": "rb_commit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284896624,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284896624,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272136528,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272136528,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513984,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513984,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461856,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461856,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505232,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505232,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580562208,
      "name": "rb_commit",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2603",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562208,
      "name": "rb_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void rb_commit(struct ring_buffer_per_cpu * cpu_buffer)
```
</details>
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
