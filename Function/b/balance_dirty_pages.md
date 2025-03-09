# Function: <code>balance_dirty_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521856,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1519",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521856,
      "name": "balance_dirty_pages.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3731
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
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580606176,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1562",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606176,
      "name": "balance_dirty_pages.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3649
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673424,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1562",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673424,
      "name": "balance_dirty_pages.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705888,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1562",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705888,
      "name": "balance_dirty_pages.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3457
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791424,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791424,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3441
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928880,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928880,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3456
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581005456,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1560",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005456,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3453
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068576,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068576,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3466
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124544,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124544,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3474
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311584,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1555",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311584,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352832,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1555",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352832,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3626
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369744,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1555",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369744,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3632
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1560",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618176,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3635
    },
    {
      "addr": 18446744071592191268,
      "name": "balance_dirty_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1557",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981840,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3703
    },
    {
      "addr": 18446744071593966642,
      "name": "balance_dirty_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied, unsigned int flags)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1669",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417968,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3643
    },
    {
      "addr": 18446744071596024925,
      "name": "balance_dirty_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied, unsigned int flags)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1669",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623184,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3643
    },
    {
      "addr": 18446744071596547128,
      "name": "balance_dirty_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied, unsigned int flags)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1669",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795008,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3699
    },
    {
      "addr": 18446744071597450845,
      "name": "balance_dirty_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492495528,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492495528,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2872
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226369296,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226369296,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3308
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285783184,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285783184,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3352
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272557330,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272557330,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3024
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093392,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093392,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3474
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040560,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040560,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3474
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084592,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084592,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3474
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
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```

```json
{
  "name": "balance_dirty_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146512,
      "name": "balance_dirty_pages",
      "external": false,
      "loc": "mm/page-writeback.c:1561",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146512,
      "name": "balance_dirty_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3519
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void balance_dirty_pages(struct bdi_writeback * wb, long unsigned int pages_dirtied)
```
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
