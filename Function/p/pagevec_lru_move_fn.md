# Function: <code>pagevec_lru_move_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539568,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:418",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:pagevec_move_tail",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:deactivate_file_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539568,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626224,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:177",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626224,
      "name": "pagevec_lru_move_fn",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693408,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:178",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693408,
      "name": "pagevec_lru_move_fn",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727312,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:188",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727312,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814352,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:188",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814352,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951712,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:189",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951712,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027872,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:188",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027872,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090000,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:189",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090000,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146720,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146720,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329984,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:206",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329984,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *) move_fn)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371232,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:204",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371232,
      "name": "pagevec_lru_move_fn",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *) move_fn)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395200,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:204",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:rotate_reclaimable_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395200,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *) move_fn)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645152,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:182",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:rotate_reclaimable_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645152,
      "name": "pagevec_lru_move_fn",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *) move_fn)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013520,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:191",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_folio",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:folio_mark_accessed",
        "mm/swap.c:folio_rotate_reclaimable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013520,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492522304,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492522304,
      "name": "pagevec_lru_move_fn",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226389968,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226389968,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285815888,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285815888,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272576300,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272576300,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115568,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115568,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062608,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062608,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106768,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106768,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *, void *) move_fn, void * arg)
```

```json
{
  "name": "pagevec_lru_move_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169040,
      "name": "pagevec_lru_move_fn",
      "external": false,
      "loc": "mm/swap.c:190",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:pagevec_move_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169040,
      "name": "pagevec_lru_move_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * arg</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*)(struct page *, struct lruvec *, void *) move_fn</code> ➡️ <code>void (*)(struct page *, struct lruvec *) move_fn</code>
</li>
</ul>
</details>
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
void pagevec_lru_move_fn(struct pagevec * pvec, void (*)(struct page *, struct lruvec *) move_fn)
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
