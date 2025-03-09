# Function: <code>pcpu_freelist_push</code>

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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450528,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450528,
      "name": "pcpu_freelist_push",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507808,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507808,
      "name": "pcpu_freelist_push",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537872,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537872,
      "name": "pcpu_freelist_push",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602304,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602304,
      "name": "pcpu_freelist_push",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697920,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:40",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697920,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770608,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:48",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770608,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855072,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855072,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906112,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906112,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052784,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:51",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052784,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065104,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:91",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065104,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079808,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:91",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079808,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307728,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:91",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307728,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606576,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:91",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606576,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990496,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:89",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990496,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181824,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:89",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181824,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330592,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:89",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:__bpf_get_stackid",
        "kernel/bpf/stackmap.c:__bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330592,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492236456,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492236456,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226131568,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226131568,
      "name": "pcpu_freelist_push",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285462656,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285462656,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382248,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382248,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874912,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874912,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821040,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821040,
      "name": "pcpu_freelist_push",
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866160,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866160,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
```

```json
{
  "name": "pcpu_freelist_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924736,
      "name": "pcpu_freelist_push",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:45",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924736,
      "name": "pcpu_freelist_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pcpu_freelist_push(struct pcpu_freelist * s, struct pcpu_freelist_node * node)
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
