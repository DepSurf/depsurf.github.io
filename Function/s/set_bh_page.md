# Function: <code>set_bh_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216800,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1475",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216800,
      "name": "set_bh_page.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581216816,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581382841,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1465",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380944,
      "name": "set_bh_page.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581380960,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581461032,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1465",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459088,
      "name": "set_bh_page.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581459104,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581516709,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1460",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515328,
      "name": "set_bh_page.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581515344,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581658748,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1420",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657392,
      "name": "set_bh_page.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581657408,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820080,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1391",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820080,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581907072,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1399",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907072,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582045640,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043984,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582044000,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123416,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121520,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582121536,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582358008,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1444",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356400,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582415574,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1443",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413168,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443227,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1463",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440304,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582767469,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1442",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762640,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583319405,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1441",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312144,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583905757,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1430",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897856,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120848,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1542",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_folio",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120848,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493666840,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493660008,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336493660032,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227196204,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227196204,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287258816,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287258816,
      "name": "set_bh_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273292586,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "mm/migrate.c:__buffer_migrate_page",
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273289990,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446743936273290010,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582092152,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090256,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582090272,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582029672,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027776,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582027792,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582082632,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080736,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582080752,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
```

```json
{
  "name": "set_bh_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582155832,
      "name": "set_bh_page",
      "external": true,
      "loc": "fs/buffer.c:1400",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153712,
      "name": "set_bh_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071582153728,
      "name": "set_bh_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void set_bh_page(struct buffer_head * bh, struct page * page, long unsigned int offset)
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
