# Function: <code>get_ksm_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830368,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:537",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830368,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956016,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:529",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956016,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029760,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:540",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029760,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076384,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:669",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076384,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187632,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:669",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187632,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332400,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:688",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332400,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
struct page * get_ksm_page(struct stable_node * stable_node, bool lock_it)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416176,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:689",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416176,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531056,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531056,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595968,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595968,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810608,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810608,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858208,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:695",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858208,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887424,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:693",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887424,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182128,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:689",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182128,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641072,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:693",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641072,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
struct page * get_ksm_page(struct ksm_stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162864,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:692",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162864,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
struct page * get_ksm_page(struct ksm_stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379072,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:728",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379072,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
struct page * get_ksm_page(struct ksm_stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583618784,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:918",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_insert",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618784,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493035456,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493035456,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226752004,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226752004,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286469552,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286469552,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272906660,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272906660,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564704,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564704,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506272,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506272,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556016,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556016,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct page * get_ksm_page(struct stable_node * stable_node, enum get_ksm_page_flags flags)
```

```json
{
  "name": "get_ksm_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621056,
      "name": "get_ksm_page",
      "external": false,
      "loc": "mm/ksm.c:694",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:remove_stable_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621056,
      "name": "get_ksm_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum get_ksm_page_flags flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool lock_it</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct stable_node * stable_node</code> ➡️ <code>struct ksm_stable_node * stable_node</code>
</li>
</ul>
</details>
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
