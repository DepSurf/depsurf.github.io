# Function: <code>read_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580532541,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580618988,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686026,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580719511,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580805146,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941680,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:111",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941680,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017664,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:113",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017664,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081616,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081616,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137600,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137600,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void read_pages(struct readahead_control * rac, struct list_head * pages, bool skip_page)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322096,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:117",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_readahead_unbounded",
        "mm/readahead.c:page_cache_readahead_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322096,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void read_pages(struct readahead_control * rac, struct list_head * pages, bool skip_page)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363952,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:117",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363952,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
void read_pages(struct readahead_control * rac, struct list_head * pages, bool skip_page)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383472,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:117",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383472,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
void read_pages(struct readahead_control * rac, struct list_head * pages, bool skip_page)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632512,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:117",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632512,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void read_pages(struct readahead_control * rac)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996096,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:146",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996096,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
void read_pages(struct readahead_control * rac)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:147",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432000,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
    },
    {
      "addr": 18446744071596024999,
      "name": "read_pages.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void read_pages(struct readahead_control * rac)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:146",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637456,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071596547202,
      "name": "read_pages.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void read_pages(struct readahead_control * rac)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:146",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808640,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
    },
    {
      "addr": 18446744071597450919,
      "name": "read_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492511384,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492511384,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226381764,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226381764,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285800656,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285800656,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272569682,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272569682,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106448,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106448,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053520,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053520,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097648,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097648,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "read_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159856,
      "name": "read_pages",
      "external": false,
      "loc": "mm/readahead.c:116",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159856,
      "name": "read_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int read_pages(struct address_space * mapping, struct file * filp, struct list_head * pages, unsigned int nr_pages, gfp_t gfp)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct readahead_control * rac</code>
</li>
<li>
<b>Param added. </b>
<code>bool skip_page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space * mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * filp</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, filp, pages, nr_pages, gfp</code> ➡️ <code>rac, pages, skip_page</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct list_head * pages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_page</code>
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
