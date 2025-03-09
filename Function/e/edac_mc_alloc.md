# Function: <code>edac_mc_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566320,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:306",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566320,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1604
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033376,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:306",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033376,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1604
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587331232,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:308",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587331232,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587509568,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:306",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587509568,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1557
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:306",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785992,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587783552,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990728,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587988288,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588843424,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:386",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843424,
      "name": "edac_mc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071588843840,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588859712,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:390",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588859712,
      "name": "edac_mc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071588860128,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588746512,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:390",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746512,
      "name": "edac_mc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
    },
    {
      "addr": 18446744071588747168,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:393",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592651262,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589437696,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:335",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594535864,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071590915904,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:334",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596312878,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071592614048,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:334",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596841758,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071593044640,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:335",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597766770,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071593796592,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501232968,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register",
        "drivers/edac/altera_edac.c:altr_sdram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501232968,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233737060,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/armada_xp_edac.c:axp_mc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233737060,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294763120,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294763120,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1792
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277927386,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277927386,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621704,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587619264,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389720,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587387280,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946872,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587944432,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```

```json
{
  "name": "edac_mc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "edac_mc_alloc",
      "external": true,
      "loc": "drivers/edac/edac_mc.c:305",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588062216,
      "name": "edac_mc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588059776,
      "name": "edac_mc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct mem_ctl_info * edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer * layers, unsigned int sz_pvt)
```
</details>
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
