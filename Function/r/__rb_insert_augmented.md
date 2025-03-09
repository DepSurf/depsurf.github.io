# Function: <code>__rb_insert_augmented</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972848,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972848,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261824,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:440",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261824,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380592,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:455",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380592,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230848,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:457",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230848,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, bool newleft, struct rb_node * * leftmost, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781696,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:491",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781696,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, bool newleft, struct rb_node * * leftmost, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159072,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:491",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159072,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, bool newleft, struct rb_node * * leftmost, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389008,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:491",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389008,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589845856,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589845856,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590071952,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071952,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069776,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_link",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069776,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219120,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_link",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219120,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585101968,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_link",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101968,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585550368,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_link",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550368,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706816,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_link",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706816,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595868832,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595868832,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596386352,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596386352,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597281600,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert",
        "drivers/gpu/drm/drm_mm.c:add_hole",
        "drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_add_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597281600,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503850992,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503850992,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236470776,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236470776,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297705232,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297705232,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279739956,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279739956,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674208,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674208,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589400000,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400000,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590117584,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117584,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void __rb_insert_augmented(struct rb_node * node, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_insert_augmented",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167968,
      "name": "__rb_insert_augmented",
      "external": true,
      "loc": "lib/rbtree.c:456",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_insert",
        "mm/interval_tree.c:vma_interval_tree_insert_after",
        "mm/interval_tree.c:vma_interval_tree_insert",
        "mm/mmap.c:__vma_link_rb",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_insert",
        "lib/interval_tree.c:interval_tree_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167968,
      "name": "__rb_insert_augmented",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool newleft</code>
</li>
<li>
<b>Param added. </b>
<code>struct rb_node * * leftmost</code>
</li>
<li>
<b>Param reordered. </b>
<code>node, root, augment_rotate</code> ➡️ <code>node, root, newleft, leftmost, augment_rotate</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>bool newleft</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rb_node * * leftmost</code>
</li>
<li>
<b>Param reordered. </b>
<code>node, root, newleft, leftmost, augment_rotate</code> ➡️ <code>node, root, augment_rotate</code>
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
