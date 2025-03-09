# Function: <code>unaccount_page_cache_page</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721328,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:185",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721328,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:185",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856880,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071580879892,
      "name": "unaccount_page_cache_page.cold.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:153",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925344,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071580953198,
      "name": "unaccount_page_cache_page.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:155",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023872,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071581048478,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079184,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071581104142,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267232,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071581286733,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:157",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309056,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071591324141,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:148",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325840,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071591266179,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:150",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572256,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071592189402,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492444840,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492444840,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226314992,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226314992,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285711120,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285711120,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272515726,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272515726,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048032,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071581072990,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995312,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071581020174,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039232,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071581064190,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
```

```json
{
  "name": "unaccount_page_cache_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unaccount_page_cache_page",
      "external": false,
      "loc": "mm/filemap.c:156",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100864,
      "name": "unaccount_page_cache_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071581125742,
      "name": "unaccount_page_cache_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void unaccount_page_cache_page(struct address_space * mapping, struct page * page)
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
