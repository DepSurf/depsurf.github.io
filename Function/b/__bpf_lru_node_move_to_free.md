# Function: <code>__bpf_lru_node_move_to_free</code>

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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508336,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:64",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508336,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538432,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:64",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538432,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602880,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:64",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602880,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698496,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:64",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698496,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771184,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:64",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771184,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855600,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855600,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906640,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906640,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055040,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053280,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581067200,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065440,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581081781,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080496,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581310073,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308560,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581609113,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607440,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581992873,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991120,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582184210,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:66",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182448,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332978,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:66",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331216,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492237480,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492237480,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226132232,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226132232,
      "name": "__bpf_lru_node_move_to_free",
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285463824,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285463824,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382974,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382974,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875440,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875440,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821504,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821504,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866688,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866688,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
```

```json
{
  "name": "__bpf_lru_node_move_to_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925264,
      "name": "__bpf_lru_node_move_to_free",
      "external": false,
      "loc": "kernel/bpf/bpf_lru_list.c:61",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925264,
      "name": "__bpf_lru_node_move_to_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __bpf_lru_node_move_to_free(struct bpf_lru_list * l, struct bpf_lru_node * node, struct list_head * free_list, enum bpf_lru_list_type tgt_free_type)
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
