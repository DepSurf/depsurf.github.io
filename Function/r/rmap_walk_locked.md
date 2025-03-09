# Function: <code>rmap_walk_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580849152,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1862",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849152,
      "name": "rmap_walk_locked",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919632,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1861",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919632,
      "name": "rmap_walk_locked",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963888,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1769",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963888,
      "name": "rmap_walk_locked",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066208,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1854",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066208,
      "name": "rmap_walk_locked",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205152,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1872",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205152,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288864,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1907",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288864,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363280,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363280,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422960,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422960,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581624764,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1955",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624928,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581671004,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1949",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671168,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581693228,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1973",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693392,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581965468,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:2374",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965536,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582381527,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:2511",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384000,
      "name": "rmap_walk_locked",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582884895,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:2525",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582887632,
      "name": "rmap_walk_locked",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583099742,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:2523",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102480,
      "name": "rmap_walk_locked",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rmap_walk_locked(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583282462,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:2682",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285280,
      "name": "rmap_walk_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492823712,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492823712,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226630436,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226630436,
      "name": "rmap_walk_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286207984,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286207984,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272780886,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272780886,
      "name": "rmap_walk_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391808,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391808,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581334512,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334512,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383008,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383008,
      "name": "rmap_walk_locked",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446896,
      "name": "rmap_walk_locked",
      "external": true,
      "loc": "mm/rmap.c:1917",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446896,
      "name": "rmap_walk_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int rmap_walk_locked(struct page * page, struct rmap_walk_control * rwc)
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
