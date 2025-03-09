# Function: <code>generic_swapfile_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753968,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:132",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753968,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875664,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:138",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875664,
      "name": "generic_swapfile_activate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943664,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:138",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943664,
      "name": "generic_swapfile_activate",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987792,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:143",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987792,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091408,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:147",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SYSC_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091408,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:147",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234275,
      "name": "generic_swapfile_activate.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581232128,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:147",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317335,
      "name": "generic_swapfile_activate.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071581315120,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428282,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581425968,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492522,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581490208,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698142,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581695760,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331528,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581742528,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:127",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274018,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581770496,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:127",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208601,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071582053152,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:80",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593986391,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071582488064,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:80",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596038374,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583002752,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:81",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560664,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071583212368,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:78",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:setup_swap_map_and_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466350,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071583447568,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492908968,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492908968,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226700540,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226700540,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286313408,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286313408,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272832862,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272832862,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461370,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581459056,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403562,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581401248,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452570,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581450256,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int generic_swapfile_activate(struct swap_info_struct * sis, struct file * swap_file, sector_t * span)
```

```json
{
  "name": "generic_swapfile_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_swapfile_activate",
      "external": true,
      "loc": "mm/page_io.c:146",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517034,
      "name": "generic_swapfile_activate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581514736,
      "name": "generic_swapfile_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
