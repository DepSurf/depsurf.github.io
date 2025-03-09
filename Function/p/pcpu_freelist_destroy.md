# Function: <code>pcpu_freelist_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450496,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450496,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507776,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507776,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537840,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537840,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602272,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602272,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697888,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697888,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770496,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:26",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770496,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854960,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854960,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906000,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906000,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052672,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052672,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064784,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064784,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079472,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079472,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307360,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307360,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606176,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606176,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989920,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989920,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181248,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181248,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330016,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:25",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330016,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492236248,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492236248,
      "name": "pcpu_freelist_destroy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226131452,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226131452,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285462352,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285462352,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382064,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382064,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874800,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874800,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820928,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820928,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866048,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866048,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924624,
      "name": "pcpu_freelist_destroy",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:23",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:prealloc_destroy",
        "kernel/bpf/stackmap.c:stack_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924624,
      "name": "pcpu_freelist_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void pcpu_freelist_destroy(struct pcpu_freelist * s)
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
