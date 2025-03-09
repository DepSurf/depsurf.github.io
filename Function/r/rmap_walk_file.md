# Function: <code>rmap_walk_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729177,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1623",
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
int rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838640,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1808",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838640,
      "name": "rmap_walk_file",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909200,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1807",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909200,
      "name": "rmap_walk_file",
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955616,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1716",
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
      "addr": 18446744071580955616,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056800,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1801",
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
      "addr": 18446744071581056800,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196208,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1819",
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
      "addr": 18446744071581196208,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279552,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1854",
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
      "addr": 18446744071581279552,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581353680,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581353680,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413184,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581413184,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613936,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1902",
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
      "addr": 18446744071581613936,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661248,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1896",
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
      "addr": 18446744071581661248,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682368,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1919",
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
      "addr": 18446744071581682368,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952272,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:2320",
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
      "addr": 18446744071581952272,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
void rmap_walk_file(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:2447",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366368,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071593978201,
      "name": "rmap_walk_file.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_file(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:2461",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582869344,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 851
    },
    {
      "addr": 18446744071596034089,
      "name": "rmap_walk_file.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void rmap_walk_file(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:2459",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086288,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071596556109,
      "name": "rmap_walk_file.cold",
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
void rmap_walk_file(struct folio * folio, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:2618",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268800,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071597460347,
      "name": "rmap_walk_file.cold",
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492813456,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446603336492813456,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226622132,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 3226622132,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286193856,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 13835058055286193856,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272774018,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446743936272774018,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382032,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581382032,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325360,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581325360,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373232,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581373232,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
```

```json
{
  "name": "rmap_walk_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437536,
      "name": "rmap_walk_file",
      "external": false,
      "loc": "mm/rmap.c:1864",
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
      "addr": 18446744071581437536,
      "name": "rmap_walk_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
int rmap_walk_file(struct page * page, struct rmap_walk_control * rwc, bool locked)
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
