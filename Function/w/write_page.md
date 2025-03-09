# Function: <code>write_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708112,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:350",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071585780944,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:285",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708112,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071585780944,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728000,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:369",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071586178976,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:283",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728000,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071586178976,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755424,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:369",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071586382848,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:286",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755424,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071586382848,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751568,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:369",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071586480768,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:287",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751568,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071586480768,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784960,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:370",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071586948368,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:287",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784960,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071586948368,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819024,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:370",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587243152,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:287",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819024,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587243152,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865728,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:370",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587424128,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:287",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865728,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587424128,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900272,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587695744,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900272,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587695744,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950496,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587900016,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950496,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587900016,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002241,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_write"
      ],
      "caller_func": [
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071588756736,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995584,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071588756736,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977872,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:376",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071588776960,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977872,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071588776960,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979840,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:376",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071588659440,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979840,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071588659440,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111072,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:376",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071589337344,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111072,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071589337344,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251072,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:380",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071590811632,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251072,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071590811632,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463642,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:378",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_write"
      ],
      "caller_func": [
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071592498864,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_unplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451136,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592498864,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580535139,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:378",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_write"
      ],
      "caller_func": [
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    },
    {
      "addr": 18446744071592929168,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:304",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521168,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592929168,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580596913,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:379",
      "file": "kernel/power/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_write"
      ],
      "caller_func": [
        "kernel/power/swap.c:swap_write_page",
        "kernel/power/swap.c:swap_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582704,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void write_page(struct bitmap * bitmap, struct page * page, int wait)
```

```json
{
  "name": "write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501134536,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501134536,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225161140,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 3233645928,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225161140,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3233645928,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
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
void write_page(struct bitmap * bitmap, struct page * page, int wait)
```

```json
{
  "name": "write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294632992,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294632992,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
void write_page(struct bitmap * bitmap, struct page * page, int wait)
```

```json
{
  "name": "write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277845464,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277845464,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:432",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587530992,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918368,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071579925416,
      "name": "write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587530992,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857504,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587299152,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857504,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587299152,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910768,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587856160,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910768,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587856160,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int write_page(void * buf, sector_t offset, struct hib_bio_batch * hb)
```

```json
{
  "name": "write_page",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956832,
      "name": "write_page",
      "external": false,
      "loc": "kernel/power/swap.c:368",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_write"
      ]
    },
    {
      "addr": 18446744071587971344,
      "name": "write_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:288",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956832,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071587971344,
      "name": "write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bitmap * bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch * hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bitmap * bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch * hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
<code>struct bitmap * bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch * hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
