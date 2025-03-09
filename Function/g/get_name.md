# Function: <code>get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041328,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:270",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041328,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582255008,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:274",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255008,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150304,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1045",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071582344480,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:274",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150304,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071582344480,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148336,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1052",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071582429456,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:275",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148336,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071582429456,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163264,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1037",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071582579872,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:275",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163264,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071582579872,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579174112,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:1089",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071582772592,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:275",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174112,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071582772592,
      "name": "get_name",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164080,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1089",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071582876592,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:276",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164080,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071582876592,
      "name": "get_name",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579176016,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1169",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583051088,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176016,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583051088,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579178464,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583157344,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178464,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583157344,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195456,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1200",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583480128,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195456,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583480128,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191136,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1200",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583588496,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191136,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583588496,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197296,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1200",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583611616,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197296,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583611616,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232704,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1213",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583970032,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232704,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071583970032,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int cpu, unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284064,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1037",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071584552560,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284064,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071584552560,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int cpu, unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349552,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1044",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071585229184,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:276",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349552,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071585229184,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int cpu, unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358416,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1040",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071585458784,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:276",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358416,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071585458784,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int cpu, unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387840,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1090",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071585693600,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:276",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387840,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071585693600,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494868584,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494868584,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228285184,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228285184,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288724400,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288724400,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int get_name(const struct path * path, char * name, struct dentry * child)
```

```json
{
  "name": "get_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274188238,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274188238,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579178720,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583126080,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178720,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583126080,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579109440,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583063232,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109440,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583063232,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579178384,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583114688,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178384,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583114688,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * get_name(unsigned int bank, struct threshold_block * b)
```

```json
{
  "name": "get_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183568,
      "name": "get_name",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:1174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks"
      ]
    },
    {
      "addr": 18446744071583203888,
      "name": "get_name",
      "external": false,
      "loc": "fs/exportfs/expfs.c:277",
      "file": "fs/exportfs/expfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exportfs/expfs.c:exportfs_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183568,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071583203888,
      "name": "get_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param added. </b>
<code>struct threshold_block * b</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param removed. </b>
<code>char * name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry * child</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>const char *</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>bank, b</code> ➡️ <code>cpu, bank, b</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param added. </b>
<code>char * name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry * child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block * b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param added. </b>
<code>char * name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry * child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block * b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param added. </b>
<code>char * name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry * child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block * b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param added. </b>
<code>char * name</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry * child</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int bank</code>
</li>
<li>
<b>Param removed. </b>
<code>struct threshold_block * b</code>
</li>
<li>
<b>Return type changed. </b>
<code>const char *</code> ➡️ <code>int</code>
</li>
</ul>
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
