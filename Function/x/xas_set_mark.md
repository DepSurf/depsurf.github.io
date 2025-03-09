# Function: <code>xas_set_mark</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589425280,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:850",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_fcntl",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425280,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589883168,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:869",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883168,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590109072,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109072,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585111952,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111952,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585261456,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:873",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261456,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145040,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:873",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145040,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597648,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:873",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345011,
      "name": "xas_set_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071585597568,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586755682,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:878",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206655,
      "name": "xas_set_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071586755568,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595920690,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:878",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375621,
      "name": "xas_set_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071595920576,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596438980,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:876",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905137,
      "name": "xas_set_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071596438864,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597334340,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:876",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830230,
      "name": "xas_set_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071597334224,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503890352,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503890352,
      "name": "xas_set_mark",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236518904,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236518904,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297756784,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297756784,
      "name": "xas_set_mark",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279781908,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279781908,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589711328,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711328,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589437104,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437104,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590154704,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154704,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590205088,
      "name": "xas_set_mark",
      "external": true,
      "loc": "lib/xarray.c:870",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_insert_entry",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205088,
      "name": "xas_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void xas_set_mark(const struct xa_state * xas, xa_mark_t mark)
```
</details>
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
