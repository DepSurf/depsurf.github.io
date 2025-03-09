# Function: <code>lpm_trie_node_alloc</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580542256,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:238",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542256,
      "name": "lpm_trie_node_alloc.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607280,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:238",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607280,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702848,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:238",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702848,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774624,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:279",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774624,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580859056,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859056,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910096,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910096,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056944,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056944,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071291,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069184,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581086265,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084176,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581315050,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:278",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312960,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581614547,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:279",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612240,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998611,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:279",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996208,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582190019,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:279",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187584,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582338851,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:282",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336352,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492242152,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492242152,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226137060,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226137060,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285470512,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285470512,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272387298,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272387298,
      "name": "lpm_trie_node_alloc",
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878896,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878896,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824960,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824960,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870144,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870144,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```

```json
{
  "name": "lpm_trie_node_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928720,
      "name": "lpm_trie_node_alloc",
      "external": false,
      "loc": "kernel/bpf/lpm_trie.c:276",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928720,
      "name": "lpm_trie_node_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct lpm_trie_node * lpm_trie_node_alloc(const struct lpm_trie * trie, const void * value)
```
</details>
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
