# Function: <code>__pcpu_freelist_push</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580450799,
      "name": "__pcpu_freelist_push",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:31",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
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
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580508082,
      "name": "__pcpu_freelist_push",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:31",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
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
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580538157,
      "name": "__pcpu_freelist_push",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:31",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
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
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580602577,
      "name": "__pcpu_freelist_push",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:31",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
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
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580698193,
      "name": "__pcpu_freelist_push",
      "external": false,
      "loc": "kernel/bpf/percpu_freelist.c:31",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770528,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770528,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854992,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854992,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906032,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906032,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052820,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:43",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052704,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581064816,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:82",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064816,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581079504,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:82",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079504,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307392,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:82",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307392,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581606208,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:82",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606208,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989968,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:80",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989968,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582181296,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:80",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181296,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582330064,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:80",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330064,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492236296,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492236296,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226131600,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226131484,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285462720,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285462416,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382106,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382106,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874832,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874832,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820960,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820960,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866080,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866080,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "__pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924656,
      "name": "__pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:37",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924656,
      "name": "__pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
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
