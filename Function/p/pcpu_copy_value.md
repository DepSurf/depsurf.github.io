# Function: <code>pcpu_copy_value</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580496992,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:555",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496992,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526224,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:637",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526224,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580589728,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:669",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589728,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685376,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:683",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685376,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580757152,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757152,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580840960,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840960,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580892000,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892000,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039136,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:806",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039136,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047824,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:827",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047824,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581062448,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:827",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062448,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581287680,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:869",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287680,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581584368,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:888",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584368,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963888,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:916",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963888,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582152256,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:931",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152256,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301408,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:948",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301408,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492220824,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492220824,
      "name": "pcpu_copy_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226116824,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226116824,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285441440,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285441440,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272366058,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272366058,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860800,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860800,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806928,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806928,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852048,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852048,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```

```json
{
  "name": "pcpu_copy_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580910384,
      "name": "pcpu_copy_value",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:697",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910384,
      "name": "pcpu_copy_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void pcpu_copy_value(struct bpf_htab * htab, void * pptr, void * value, bool onallcpus)
```
</details>
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
