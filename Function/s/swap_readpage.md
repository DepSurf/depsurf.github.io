# Function: <code>swap_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int swap_readpage(struct page * page)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755248,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:324",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755248,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int swap_readpage(struct page * page)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877104,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:335",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877104,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int swap_readpage(struct page * page)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945152,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:332",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945152,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int swap_readpage(struct page * page, bool do_poll)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989312,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:337",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989312,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093024,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093024,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233728,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233728,
      "name": "swap_readpage",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316752,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:351",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316752,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427712,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427712,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491952,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491952,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697456,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:353",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697456,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744256,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:375",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744256,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772304,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:356",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772304,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054944,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:356",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054944,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
int swap_readpage(struct page * page, bool synchronous, struct swap_iocb * * plug)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:448",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593986720,
      "name": "swap_readpage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071582491680,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
int swap_readpage(struct page * page, bool synchronous, struct swap_iocb * * plug)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:448",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596038792,
      "name": "swap_readpage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583006400,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
void swap_readpage(struct page * page, bool synchronous, struct swap_iocb * * plug)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:496",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560999,
      "name": "swap_readpage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583215536,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492910816,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492910816,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226702556,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226702556,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286315952,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286315952,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272834384,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272834384,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460800,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460800,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402992,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402992,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581452000,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452000,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int swap_readpage(struct page * page, bool synchronous)
```

```json
{
  "name": "swap_readpage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516464,
      "name": "swap_readpage",
      "external": true,
      "loc": "mm/page_io.c:350",
      "file": "mm/page_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:read_swap_cache_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516464,
      "name": "swap_readpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool do_poll</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool synchronous</code>
</li>
<li>
<b>Param removed. </b>
<code>bool do_poll</code>
</li>
</ul>
</details>
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
<code>struct swap_iocb * * plug</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void swap_readpage(struct page * page, bool synchronous, struct swap_iocb * * plug)
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
