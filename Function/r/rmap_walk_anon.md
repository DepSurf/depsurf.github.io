# Function: <code>rmap_walk_anon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729463,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1579",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839248,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1755",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839248,
      "name": "rmap_walk_anon",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909808,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1754",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909808,
      "name": "rmap_walk_anon",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956192,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1664",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956192,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057392,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1749",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057392,
      "name": "rmap_walk_anon",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195600,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195600,
      "name": "rmap_walk_anon",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278928,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1802",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278928,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581353072,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353072,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412576,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412576,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612784,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1850",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612784,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660624,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1844",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660624,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683008,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1866",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683008,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951648,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:2267",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951648,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_anon(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:2399",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365440,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
    },
    {
      "addr": 18446744071593978180,
      "name": "rmap_walk_anon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_anon(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:2413",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868496,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071596034068,
      "name": "rmap_walk_anon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_anon(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:2411",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085792,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071596556089,
      "name": "rmap_walk_anon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_anon(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:2569",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268336,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071597460327,
      "name": "rmap_walk_anon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492812384,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492812384,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226621768,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226621768,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286192992,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286192992,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272773594,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272773594,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381424,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381424,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324752,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324752,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372624,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372624,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
void rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_anon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436944,
      "name": "rmap_walk_anon",
      "external": false,
      "loc": "mm/rmap.c:1812",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:rmap_walk_locked",
        "mm/rmap.c:rmap_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436944,
      "name": "rmap_walk_anon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int rmap_walk_anon(struct page * page, struct rmap_walk_control * rwc, bool locked)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
