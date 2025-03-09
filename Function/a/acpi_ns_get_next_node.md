# Function: <code>acpi_ns_get_next_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691930,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:68",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691930,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584016453,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:68",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016304,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158421,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:68",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158272,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584225685,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:68",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225551,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570669,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:68",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570463,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584795807,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795601,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584898198,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897992,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585101180,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100974,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585237538,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237332,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585943337,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943131,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586066285,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066079,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585943113,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942907,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586431406,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431200,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587682546,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682272,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588992596,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992320,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589283108,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282832,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589589828,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589552,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497563492,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497563260,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095525,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095395,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010879,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010749,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585189122,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188916,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```

```json
{
  "name": "acpi_ns_get_next_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585295282,
      "name": "acpi_ns_get_next_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:34",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295076,
      "name": "acpi_ns_get_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_namespace_node * acpi_ns_get_next_node(struct acpi_namespace_node * parent_node, struct acpi_namespace_node * child_node)
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
