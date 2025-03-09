# Function: <code>xas_clear_mark</code>

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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589428928,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:879",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_reserve",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428928,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589886592,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:898",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886592,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112544,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112544,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585111792,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111792,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585261296,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:902",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261296,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585144880,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:902",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144880,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597782,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:902",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345112,
      "name": "xas_clear_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071585597696,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586756056,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:907",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206756,
      "name": "xas_clear_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071586755936,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595922680,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:907",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375889,
      "name": "xas_clear_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071595922560,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596441398,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:905",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905395,
      "name": "xas_clear_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071596441264,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597336758,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:905",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_store",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830488,
      "name": "xas_clear_mark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071597336624,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503893928,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503893928,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236523088,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236523088,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297761616,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297761616,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279784142,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279784142,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589714800,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714800,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589440576,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440576,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590158176,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590158176,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
```

```json
{
  "name": "xas_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590208752,
      "name": "xas_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:899",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xas_init_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208752,
      "name": "xas_clear_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xas_clear_mark(const struct xa_state * xas, xa_mark_t mark)
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
