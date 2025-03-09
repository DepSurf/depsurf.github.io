# Function: <code>ext4_es_free_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838368,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:356",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838368,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582033568,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:356",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033568,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123680,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:356",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123680,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922912,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:356",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922912,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582073184,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:357",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073184,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582261248,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:356",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261248,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582357760,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357760,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582525792,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525792,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582625376,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625376,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933840,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933840,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583008384,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:481",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008384,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035840,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:481",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035840,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583373264,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:481",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373264,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882560,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:481",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882560,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507088,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:479",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507088,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735584,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:496",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735584,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967920,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:510",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967920,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494274784,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494274784,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227708712,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227708712,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287986256,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287986256,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273722224,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273722224,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582594112,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594112,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582531280,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531280,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582584224,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584224,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void ext4_es_free_extent(struct inode * inode, struct extent_status * es)
```

```json
{
  "name": "ext4_es_free_extent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582665776,
      "name": "ext4_es_free_extent",
      "external": false,
      "loc": "fs/ext4/extents_status.c:472",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:es_do_reclaim_extents",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665776,
      "name": "ext4_es_free_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
