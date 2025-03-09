# Function: <code>__bpf_lru_list_shrink</code>

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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580509168,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:259",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509168,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539072,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:258",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539072,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580603520,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:258",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603520,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699136,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:258",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699136,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580771824,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:258",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771824,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580856256,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856256,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580907296,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907296,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581054128,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054128,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066288,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066288,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581081120,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081120,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581309184,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309184,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608144,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608144,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991888,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991888,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582183216,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:260",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183216,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582331984,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:260",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331984,
      "name": "__bpf_lru_list_shrink.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492238384,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492238384,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226133056,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226133056,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285464976,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285464976,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272383724,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272383724,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580876096,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876096,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822160,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822160,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580867344,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867344,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_list_shrink",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580925920,
      "name": "__bpf_lru_list_shrink",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:255",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925920,
      "name": "__bpf_lru_list_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
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
unsigned int __bpf_lru_list_shrink(struct bpf_lru * lru, struct bpf_lru_list * l, unsigned int tgt_nshrink, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```
</details>
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
