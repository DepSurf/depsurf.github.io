# Function: <code>acpi_os_acquire_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583678980,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703989,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071583732164,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735380,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703989,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002692,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584028386,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584056410,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059646,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028386,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584144140,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584170307,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584198248,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584201493,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170307,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584211384,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584237791,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584265859,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584269097,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237791,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544644,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584589096,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584634593,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639753,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:99",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589096,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584769119,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584814620,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584860311,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584865458,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814620,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584870820,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917340,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071584963805,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584968957,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917340,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585074688,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585120011,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585166976,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172193,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120011,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211022,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585256373,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585303323,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585308550,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256373,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585916859,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585962302,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071586010052,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586015077,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962302,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586038569,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085220,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071586132864,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137872,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085220,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585915393,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585962023,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071586009407,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586014638,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962023,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403472,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586450377,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071586499430,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504986,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586450377,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587652817,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587702115,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071587754619,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587760526,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702115,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588956627,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016586,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081416,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088901,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
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
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589246627,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589307146,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589373160,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380741,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
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
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589553251,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589613914,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589680264,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687893,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497545608,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497577220,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446603336497616328,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497620380,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497577220,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585080794,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108357,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585137766,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585140951,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108357,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584996205,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023684,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585052979,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056151,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023684,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585162606,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585207957,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585254907,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585260134,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207957,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_acquire_object(struct kmem_cache * cache)
```

```json
{
  "name": "acpi_os_acquire_object",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268766,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585314117,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    },
    {
      "addr": 18446744071585361067,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366294,
      "name": "acpi_os_acquire_object",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:65",
      "file": "drivers/acpi/acpica/utstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314117,
      "name": "acpi_os_acquire_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * acpi_os_acquire_object(struct kmem_cache * cache)
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
