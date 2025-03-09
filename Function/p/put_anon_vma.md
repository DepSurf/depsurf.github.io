# Function: <code>put_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580726992,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:105",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071580829510,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:105",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/ksm.c:remove_rmap_item_from_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887042,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:105",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906070,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:105",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726992,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847973,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:109",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071580957348,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:109",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016061,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:109",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038846,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:109",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846304,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918853,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:110",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581031108,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:110",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090251,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:110",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114030,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:110",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916800,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963045,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581077989,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137756,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162555,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961184,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581065365,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581189330,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258520,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288943,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063504,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581204359,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581334094,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405704,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435918,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202432,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581288071,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581417870,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489183,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519550,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286144,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581362513,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581532924,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596489,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629713,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360560,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581422193,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581597820,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667049,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700582,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420240,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581623955,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581812448,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884279,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916161,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621984,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581670197,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:111",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581860028,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:111",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930456,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:111",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962943,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668192,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581692421,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581889248,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581955801,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989064,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690416,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963813,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071582183949,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260547,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291171,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:108",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961808,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582383849,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071582643224,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726809,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775696,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381760,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582887393,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071583163848,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254827,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309433,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885168,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583102241,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071583380056,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476281,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583528735,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100016,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583285061,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071583619752,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669235,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723270,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:move_pages_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902932,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:113",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282736,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492822732,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493037616,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493110480,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493143800,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226629416,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 3226753820,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 3226806836,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226627152,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286206704,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 13835058055286472568,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286585300,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286631524,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286203328,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272780028,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272907952,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272956746,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391041,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581566556,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581635785,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669318,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389088,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581333745,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581508124,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576745,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608854,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331792,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581382241,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581557868,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627097,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660630,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380288,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "put_anon_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581446124,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": [
        "mm/rmap.c:anon_vma_fork"
      ]
    },
    {
      "addr": 18446744071581618450,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693412,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727012,
      "name": "put_anon_vma",
      "external": false,
      "loc": "include/linux/rmap.h:112",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444144,
      "name": "put_anon_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
void put_anon_vma(struct anon_vma * anon_vma)
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
void put_anon_vma(struct anon_vma * anon_vma)
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
