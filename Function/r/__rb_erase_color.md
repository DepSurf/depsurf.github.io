# Function: <code>__rb_erase_color</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970992,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:396",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/mmap.c:vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970992,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259968,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:396",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259968,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583378736,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:411",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378736,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588228928,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:411",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588228928,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588778912,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:426",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778912,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589159936,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:426",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159936,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589389872,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:426",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389872,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589844528,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589844528,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590070624,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590070624,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067712,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067712,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217008,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217008,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585099856,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099856,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585548256,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548256,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704160,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704160,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595866032,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595866032,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596383376,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596383376,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597278624,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__dequeue_entity",
        "mm/interval_tree.c:__anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove",
        "drivers/gpu/drm/drm_mm.c:rm_hole",
        "drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597278624,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503848640,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503848640,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236468300,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236468300,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297703152,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297703152,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279738314,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__free_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279738314,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589672880,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672880,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589398672,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398672,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116256,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116256,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
void __rb_erase_color(struct rb_node * parent, struct rb_root * root, void (*)(struct rb_node *, struct rb_node *) augment_rotate)
```

```json
{
  "name": "__rb_erase_color",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166640,
      "name": "__rb_erase_color",
      "external": true,
      "loc": "lib/rbtree.c:410",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "arch/x86/mm/pat_rbtree.c:rbt_memtype_erase",
        "mm/interval_tree.c:anon_vma_interval_tree_remove",
        "mm/interval_tree.c:vma_interval_tree_remove",
        "mm/mmap.c:__vma_rb_erase",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "lib/interval_tree.c:interval_tree_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166640,
      "name": "__rb_erase_color",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
