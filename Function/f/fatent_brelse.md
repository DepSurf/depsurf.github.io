# Function: <code>fatent_brelse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581947776,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:336",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962784,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:336",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071581968822,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:336",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983822,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:336",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962784,
      "name": "fatent_brelse",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159257,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582179459,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071582181208,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196809,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174784,
      "name": "fatent_brelse",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582248665,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268867,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071582270684,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286313,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264192,
      "name": "fatent_brelse",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582333601,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353553,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355356,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370809,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:339",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582484161,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504321,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506156,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521593,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582675309,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695358,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071582697227,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713017,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:340",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690656,
      "name": "fatent_brelse",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582777181,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798056,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800281,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817049,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582951268,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972594,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975207,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992041,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583057924,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079202,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081415,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098233,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583377059,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397626,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071583400042,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583417177,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391648,
      "name": "fatent_brelse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583492995,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583513274,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071583515559,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583531609,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507296,
      "name": "fatent_brelse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583514977,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536390,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071583538455,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583554789,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530352,
      "name": "fatent_brelse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583870469,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894014,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071583896353,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583913332,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887296,
      "name": "fatent_brelse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584444076,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470384,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": [
        "fs/fat/fatent.c:fat_ent_read"
      ]
    },
    {
      "addr": 18446744071584472932,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584490959,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463296,
      "name": "fatent_brelse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585106604,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585134016,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585136660,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585157009,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585335852,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363360,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366004,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585386145,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585570524,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585598096,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600740,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585621009,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:369",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494756852,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494784420,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494786592,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494805300,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228181848,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 3228204540,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3228207032,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3228224664,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288587736,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288618588,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288621496,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288644496,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274099152,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274116300,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274118136,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274133388,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583026660,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047938,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050151,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066969,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582963812,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985090,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987303,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004121,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583015268,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036546,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038759,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055577,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatent_brelse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583104415,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125682,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_count_free_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/fatent.c:fat_ent_read",
        "fs/fat/fatent.c:fat_ent_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583127895,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/file.c:fat_truncate_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144777,
      "name": "fatent_brelse",
      "external": false,
      "loc": "fs/fat/fat.h:368",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_chain_add"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void fatent_brelse(struct fat_entry * fatent)
```
</details>
</li>
</ul>
