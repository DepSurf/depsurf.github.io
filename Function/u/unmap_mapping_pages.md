# Function: <code>unmap_mapping_pages</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126720,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2862",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126720,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205968,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2599",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205968,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280384,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2667",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280384,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339104,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339104,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581536864,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3040",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536864,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580240,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3203",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580240,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601376,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3294",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601376,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865952,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3391",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865952,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582262790,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3549",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_mapping_range"
      ],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/memory.c:__do_fault",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262128,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582754710,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3521",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_mapping_range"
      ],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/memory.c:__do_fault",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753968,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582970198,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3524",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_mapping_range"
      ],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/memory.c:__do_fault",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969456,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583148742,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:3603",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_mapping_range"
      ],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148352,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492745088,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492745088,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226577236,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226577236,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286101152,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286101152,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272729926,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272729926,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307952,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307952,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251760,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251760,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299152,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299152,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
```

```json
{
  "name": "unmap_mapping_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363136,
      "name": "unmap_mapping_pages",
      "external": true,
      "loc": "mm/memory.c:2692",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/memory.c:unmap_mapping_range",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363136,
      "name": "unmap_mapping_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void unmap_mapping_pages(struct address_space * mapping, long unsigned int start, long unsigned int nr, bool even_cows)
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
