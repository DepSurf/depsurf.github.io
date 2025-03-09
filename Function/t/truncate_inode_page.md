# Function: <code>truncate_inode_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580544064,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:149",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544064,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632944,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:156",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632944,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700144,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:183",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700144,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580733952,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:181",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733952,
      "name": "truncate_inode_page",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580818527,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:226",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820832,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955439,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:222",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957680,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581031631,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:219",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033904,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581095651,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097872,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581152563,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154800,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341632,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343344,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581383662,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385072,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403951,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:211",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405280,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581653625,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:211",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656480,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492530428,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492532928,
      "name": "truncate_inode_page",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226396176,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226398116,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285825492,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285827968,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272582316,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272584176,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121411,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123648,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068403,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070624,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581112611,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114848,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int truncate_inode_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "truncate_inode_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581175091,
      "name": "truncate_inode_page",
      "external": true,
      "loc": "mm/truncate.c:220",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:generic_error_remove_page"
      ],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177296,
      "name": "truncate_inode_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int truncate_inode_page(struct address_space * mapping, struct page * page)
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
