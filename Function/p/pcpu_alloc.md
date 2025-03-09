# Function: <code>pcpu_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618720,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:873",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_percpu_gfp",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_reserved_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618720,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1634
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721520,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:868",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721520,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1587
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580787328,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:868",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787328,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1610
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825904,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:859",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825904,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1717
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918800,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1343",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918800,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1567
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1341",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052944,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1539
    },
    {
      "addr": 18446744071581057766,
      "name": "pcpu_alloc.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1352",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130720,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1554
    },
    {
      "addr": 18446744071581135587,
      "name": "pcpu_alloc.cold.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198400,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1572
    },
    {
      "addr": 18446744071581201244,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256864,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071581259637,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1558",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446000,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1682
    },
    {
      "addr": 18446744071581448959,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1676",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489536,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1975
    },
    {
      "addr": 18446744071591326334,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1677",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508944,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1997
    },
    {
      "addr": 18446744071591268383,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1722",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772144,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1898
    },
    {
      "addr": 18446744071592194280,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1722",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155344,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2135
    },
    {
      "addr": 18446744071593970814,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1719",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635200,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2089
    },
    {
      "addr": 18446744071596028191,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1719",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844400,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
    },
    {
      "addr": 18446744071596550588,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1717",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018928,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2104
    },
    {
      "addr": 18446744071597454253,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492659280,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492659280,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2316
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226498040,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226498040,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1944
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285976112,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285976112,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2288
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272668204,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272668204,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225712,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071581228485,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172384,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071581175157,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216912,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071581219685,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp)
```

```json
{
  "name": "pcpu_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_alloc",
      "external": false,
      "loc": "mm/percpu.c:1586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__alloc_reserved_percpu",
        "mm/percpu.c:__alloc_percpu",
        "mm/percpu.c:__alloc_percpu_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280288,
      "name": "pcpu_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071581283109,
      "name": "pcpu_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
