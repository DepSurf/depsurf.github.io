# Function: <code>total_swapcache_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755536,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:52",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755536,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580877572,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:52",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877504,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945588,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:54",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945520,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989808,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:51",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989808,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093728,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093728,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234480,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234480,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317536,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317536,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428512,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428512,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492752,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492752,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698976,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:70",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698976,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745760,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745760,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591274047,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:433",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897832,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:433",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592208761,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:439",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231551,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:439",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593986772,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:453",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730256,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:453",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583008069,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:458",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343232,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:458",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583216389,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:453",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573328,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:453",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
  "name": "total_swapcache_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583451893,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:445",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:show_swap_cache_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584805088,
      "name": "total_swapcache_pages",
      "external": false,
      "loc": "include/linux/swap.h:445",
      "file": "fs/proc/meminfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492911992,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492911992,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226703588,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226703588,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286317456,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286317456,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272835176,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272835176,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461600,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461600,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403792,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403792,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581452800,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452800,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int total_swapcache_pages()
```

```json
{
  "name": "total_swapcache_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517264,
      "name": "total_swapcache_pages",
      "external": true,
      "loc": "mm/swap_state.c:71",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:show_swap_cache_info",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "fs/proc/meminfo.c:meminfo_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517264,
      "name": "total_swapcache_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int total_swapcache_pages()
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
