# Function: <code>agp_free_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584209392,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:60",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209392,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584209424,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551072,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:60",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548800,
      "name": "agp_free_key.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584548832,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584732480,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:60",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730752,
      "name": "agp_free_key.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584730784,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584814484,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812848,
      "name": "agp_free_key.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584812880,
      "name": "agp_free_key",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585235332,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233616,
      "name": "agp_free_key.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585233648,
      "name": "agp_free_key",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585471127,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469904,
      "name": "agp_free_key.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585469936,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585593655,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585593248,
      "name": "agp_free_key.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585593280,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813687,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813264,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585813296,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585956327,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585955904,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585955936,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586697850,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695120,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586695152,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586800586,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797856,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586797888,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586680983,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586678240,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586678272,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587229623,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226768,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587226800,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588536750,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_free_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588534976,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588536016,
      "name": "agp_free_key",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589982398,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_free_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589980640,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589981616,
      "name": "agp_free_key",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590291998,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_free_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590290272,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071590291232,
      "name": "agp_free_key",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590633214,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:61",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_free_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_free_memory",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590631408,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071590632352,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291952892,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291950992,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055291951072,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585717303,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716880,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585716912,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585576487,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576064,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585576096,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585906343,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905920,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585905952,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void agp_free_key(int key)
```

```json
{
  "name": "agp_free_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586014327,
      "name": "agp_free_key",
      "external": true,
      "loc": "drivers/char/agp/generic.c:62",
      "file": "drivers/char/agp/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory"
      ],
      "caller_func": [
        "drivers/char/agp/generic.c:agp_generic_alloc_user",
        "drivers/char/agp/generic.c:agp_generic_free_by_type",
        "drivers/char/agp/generic.c:agp_create_memory",
        "drivers/char/agp/intel-gtt.c:intel_i810_free_by_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013904,
      "name": "agp_free_key.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586013936,
      "name": "agp_free_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void agp_free_key(int key)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void agp_free_key(int key)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void agp_free_key(int key)
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
