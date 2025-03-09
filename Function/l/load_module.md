# Function: <code>load_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579928464,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3421",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_init_module",
        "kernel/module.c:SYSC_finit_module"
      ]
    },
    {
      "addr": 18446744071585821850,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928464,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958336,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3574",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/module.c:SYSC_init_module"
      ]
    },
    {
      "addr": 18446744071586215930,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958336,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7617
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
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579989280,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3589",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/module.c:SYSC_init_module"
      ]
    },
    {
      "addr": 18446744071586420426,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989280,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7275
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
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995056,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3632",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/module.c:SYSC_init_module"
      ]
    },
    {
      "addr": 18446744071586525002,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995056,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7955
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
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580041536,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3654",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_finit_module",
        "kernel/module.c:SYSC_init_module"
      ]
    },
    {
      "addr": 18446744071586992538,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041536,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags, bool can_do_ima_check)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3686",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587290602,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099808,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6322
    },
    {
      "addr": 18446744071580108651,
      "name": "load_module.cold.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3686",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587470634,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146624,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6591
    },
    {
      "addr": 18446744071580155640,
      "name": "load_module.cold.78",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3718",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587743932,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194432,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4628
    },
    {
      "addr": 18446744071580201625,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587948188,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242688,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4601
    },
    {
      "addr": 18446744071580249884,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071588800782,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314064,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1758
    },
    {
      "addr": 18446744071580318758,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3988",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071588818206,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580299520,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
    },
    {
      "addr": 18446744071591314012,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3888",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071588704574,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302112,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2828
    },
    {
      "addr": 18446744071591256317,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3900",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071589393214,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455408,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2992
    },
    {
      "addr": 18446744071592159442,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module/main.c:2650",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_finit_module",
        "kernel/module/main.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071590869671,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:45",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479568,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3272
    },
    {
      "addr": 18446744071593924782,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module/main.c:2694",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_finit_module",
        "kernel/module/main.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071592562567,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:45",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729072,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3409
    },
    {
      "addr": 18446744071595993989,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module/main.c:2820",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:init_module_from_file",
        "kernel/module/main.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071592993015,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808320,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3308
    },
    {
      "addr": 18446744071596512309,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module/main.c:2831",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:init_module_from_file",
        "kernel/module/main.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071593744119,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:46",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897712,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3308
    },
    {
      "addr": 18446744071597411510,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491484944,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446603336501186912,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491484944,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225467240,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__se_sys_finit_module",
        "kernel/module.c:__se_sys_init_module"
      ]
    },
    {
      "addr": 3233693816,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225467240,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284439344,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 13835058055294702624,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284439344,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271929454,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446743936277889424,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271929454,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4422
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587579164,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211488,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4601
    },
    {
      "addr": 18446744071580218684,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587347244,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158928,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4601
    },
    {
      "addr": 18446744071580166124,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071587904332,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202960,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4601
    },
    {
      "addr": 18446744071580210156,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int load_module(struct load_info * info, const char * uargs, int flags)
```

```json
{
  "name": "load_module",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "load_module",
      "external": false,
      "loc": "kernel/module.c:3785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_finit_module",
        "kernel/module.c:__do_sys_init_module"
      ]
    },
    {
      "addr": 18446744071588019596,
      "name": "load_module",
      "external": false,
      "loc": "drivers/md/dm-target.c:44",
      "file": "drivers/md/dm-target.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-target.c:dm_get_target_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255424,
      "name": "load_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4616
    },
    {
      "addr": 18446744071580262835,
      "name": "load_module.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool can_do_ima_check</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool can_do_ima_check</code>
</li>
</ul>
</details>
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
