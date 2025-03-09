# Function: <code>cancel_dirty_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cancel_dirty_page(struct page * page)
```

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580530976,
      "name": "cancel_dirty_page",
      "external": true,
      "loc": "mm/page-writeback.c:2611",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530976,
      "name": "cancel_dirty_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void cancel_dirty_page(struct page * page)
```

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617184,
      "name": "cancel_dirty_page",
      "external": true,
      "loc": "mm/page-writeback.c:2656",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617184,
      "name": "cancel_dirty_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void cancel_dirty_page(struct page * page)
```

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684224,
      "name": "cancel_dirty_page",
      "external": true,
      "loc": "mm/page-writeback.c:2623",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684224,
      "name": "cancel_dirty_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void cancel_dirty_page(struct page * page)
```

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580717568,
      "name": "cancel_dirty_page",
      "external": true,
      "loc": "mm/page-writeback.c:2626",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_page",
        "fs/buffer.c:try_to_free_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717568,
      "name": "cancel_dirty_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580818408,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1483",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661740,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1483",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580955332,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1570",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825196,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1570",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581031524,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1640",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912332,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1640",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145236,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1640",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581095495,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1652",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049472,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1652",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305440,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1652",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581152407,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127328,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404464,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581338743,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1811",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366756,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1811",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695679,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1811",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581380695,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1856",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582425540,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1856",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582769056,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1856",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581401487,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1864",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453219,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1864",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798176,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1864",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581651999,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1893",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775938,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1893",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124381,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1893",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492530256,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493664424,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494000680,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226396012,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227202236,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3227470992,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285825204,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287270272,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287653296,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272582158,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273297176,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273517470,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581121255,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096064,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373200,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068247,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033536,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310896,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581112455,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086544,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363680,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cancel_dirty_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581174935,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582159229,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443424,
      "name": "cancel_dirty_page",
      "external": false,
      "loc": "include/linux/mm.h:1624",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void cancel_dirty_page(struct page * page)
```
</details>
</li>
</ul>
