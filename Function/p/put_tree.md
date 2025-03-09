# Function: <code>put_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068576,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:97",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:free_chunk",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068576,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108591,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:97",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:free_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101840,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148911,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:97",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:free_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142112,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154700,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:98",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147888,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580207548,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:99",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200576,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580267563,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:99",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_one",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260608,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320139,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313696,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372430,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366304,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421182,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415056,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580501198,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494496,
      "name": "put_tree",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580489278,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482576,
      "name": "put_tree",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580494261,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486464,
      "name": "put_tree",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661829,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654112,
      "name": "put_tree",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580871829,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863312,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581160293,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151424,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581253698,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244768,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359938,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_kill_trees",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:prune_tree_thread",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:trim_marked",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351024,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491688304,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225641328,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225634736,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284702140,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284693920,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272077286,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:free_chunk",
        "kernel/audit_tree.c:free_chunk"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580389982,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383856,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580337150,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331024,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381230,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375104,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void put_tree(struct audit_tree * tree)
```

```json
{
  "name": "put_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436732,
      "name": "put_tree",
      "external": false,
      "loc": "kernel/audit_tree.c:116",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_put_tree",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:audit_put_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": [
        "kernel/audit_tree.c:audit_add_tree_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430624,
      "name": "put_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void put_tree(struct audit_tree * tree)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void put_tree(struct audit_tree * tree)
```
</details>
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
