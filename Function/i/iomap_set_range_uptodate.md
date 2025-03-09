# Function: <code>iomap_set_range_uptodate</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135344,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap.c:206",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_end",
        "fs/iomap.c:iomap_read_page_sync",
        "fs/iomap.c:iomap_readpage_actor",
        "fs/iomap.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135344,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582299344,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299344,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582398336,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582398336,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582690464,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:163",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690464,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582762224,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:161",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_page_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762224,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582790208,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:161",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790208,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583116224,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:161",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116224,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583605502,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:154",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584210160,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:162",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584439903,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:162",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct folio * folio, size_t off, size_t len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584657936,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:72",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657936,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494001712,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494001712,
      "name": "iomap_set_range_uptodate",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227462676,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227462676,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287645616,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287645616,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273513412,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273513412,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367072,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367072,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304768,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304768,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357552,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357552,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582437152,
      "name": "iomap_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:121",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437152,
      "name": "iomap_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void iomap_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void iomap_set_range_uptodate(struct folio * folio, size_t off, size_t len)
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
