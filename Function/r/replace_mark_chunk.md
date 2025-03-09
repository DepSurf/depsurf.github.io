# Function: <code>replace_mark_chunk</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315793,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314144,
      "name": "replace_mark_chunk.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580314160,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368026,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366352,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580366368,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580416778,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415104,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580415120,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580495570,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:replace_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580483650,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:replace_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580487538,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580655186,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580864014,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581152158,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581245517,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581351773,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:279",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:create_chunk",
        "kernel/audit_tree.c:replace_chunk"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491682204,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491680808,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336491680832,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225635288,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225634792,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225634816,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284693020,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_freeing_mark",
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284691792,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272071700,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272070382,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446743936272070402,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580385578,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383904,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580383920,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332746,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331072,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580331088,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580376826,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375152,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580375168,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
```

```json
{
  "name": "replace_mark_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580432354,
      "name": "replace_mark_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:281",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:replace_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430672,
      "name": "replace_mark_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071580430688,
      "name": "replace_mark_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void replace_mark_chunk(struct fsnotify_mark * mark, struct audit_chunk * chunk)
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
