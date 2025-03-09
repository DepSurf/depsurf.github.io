# Function: <code>pcpu_freelist_pop</code>

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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450880,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:77",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450880,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508160,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:77",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508160,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538256,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:77",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538256,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602672,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:77",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602672,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698288,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:77",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698288,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771120,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:112",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771120,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855536,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855536,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906576,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906576,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053216,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053216,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065360,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065360,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581080416,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080416,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308480,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308480,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607376,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:200",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607376,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990992,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:191",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990992,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182320,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:191",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182320,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331088,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:191",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331088,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492237320,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492237320,
      "name": "pcpu_freelist_pop",
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226132192,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226132192,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285463728,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285463728,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382916,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382916,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875376,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875376,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821472,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821472,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866624,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866624,
      "name": "pcpu_freelist_pop",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925200,
      "name": "pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:109",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925200,
      "name": "pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct pcpu_freelist_node * pcpu_freelist_pop(struct pcpu_freelist * s)
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
