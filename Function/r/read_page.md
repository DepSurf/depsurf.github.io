# Function: <code>read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773760,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:356",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773760,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586171376,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:354",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171376,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375104,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:357",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375104,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586477360,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/bitmap.c:358",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477360,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944960,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:358",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944960,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:358",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240304,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071587258182,
      "name": "read_page.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:358",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421056,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    },
    {
      "addr": 18446744071587438806,
      "name": "read_page.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693008,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071587711144,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897296,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071587915448,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588752736,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071588766982,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772992,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071591590881,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657040,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    },
    {
      "addr": 18446744071591533993,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334912,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071592645633,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590807232,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    },
    {
      "addr": 18446744071594529965,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592493408,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071596310303,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:367",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592922864,
      "name": "read_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
    },
    {
      "addr": 18446744071596839671,
      "name": "read_page.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501129024,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501129024,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233642608,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233642608,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294627776,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294627776,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277843050,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277843050,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528272,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071587546424,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296432,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071587314520,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853440,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071587871592,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
```

```json
{
  "name": "read_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_page",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:359",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968352,
      "name": "read_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071587986712,
      "name": "read_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int read_page(struct file * file, long unsigned int index, struct bitmap * bitmap, long unsigned int count, struct page * page)
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
