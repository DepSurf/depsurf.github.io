# Function: <code>klp_init_object_loaded</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579798816,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:700",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798816,
      "name": "klp_init_object_loaded.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828718,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:767",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826144,
      "name": "klp_init_object_loaded.isra.13.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856128,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:768",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856128,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860528,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:629",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860528,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902176,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:643",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902176,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:705",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935936,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579938167,
      "name": "klp_init_object_loaded.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579983280,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:705",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_register_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982992,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579985255,
      "name": "klp_init_object_loaded.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580023250,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022944,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071580026219,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580074274,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073968,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071580077172,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:772",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133408,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071580136504,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:772",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111632,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071591309639,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:771",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115440,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071591251689,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:771",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257696,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071592147532,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:771",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426976,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071593920229,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:796",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667744,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071595992292,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:824",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743648,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596510441,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:824",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming",
        "kernel/livepatch/core.c:klp_init_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828720,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071597409314,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284194976,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284194976,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580043010,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042704,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071580045908,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579988322,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988016,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071579991220,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034546,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034240,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071580037444,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```

```json
{
  "name": "klp_init_object_loaded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085250,
      "name": "klp_init_object_loaded",
      "external": false,
      "loc": "kernel/livepatch/core.c:716",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_module_coming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084944,
      "name": "klp_init_object_loaded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071580088148,
      "name": "klp_init_object_loaded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```
</details>
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
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
int klp_init_object_loaded(struct klp_patch * patch, struct klp_object * obj)
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
