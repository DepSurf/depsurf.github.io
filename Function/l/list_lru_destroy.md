# Function: <code>list_lru_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652496,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:567",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:destroy_super",
        "fs/super.c:destroy_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652496,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759760,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:567",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:destroy_super",
        "fs/super.c:destroy_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759760,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824960,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:569",
      "file": "mm/list_lru.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:destroy_super",
        "fs/super.c:destroy_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824960,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580867008,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:567",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:destroy_super",
        "fs/super.c:destroy_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867008,
      "name": "list_lru_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580958240,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:568",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958240,
      "name": "list_lru_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581092272,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:591",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:workingset_init",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092272,
      "name": "list_lru_destroy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581169936,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:641",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169936,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581240976,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240976,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581299424,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299424,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581490144,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:630",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490144,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581531808,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:630",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531808,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581553312,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:622",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553312,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581817706,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:622",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592197271,
      "name": "list_lru_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581817680,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582207166,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:589",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593973946,
      "name": "list_lru_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582207136,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582694078,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:589",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596030933,
      "name": "list_lru_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582694048,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582907982,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:589",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596552908,
      "name": "list_lru_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582907952,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583081918,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:590",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_pool_destroy",
        "mm/zswap.c:zswap_pool_create",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597456665,
      "name": "list_lru_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583081888,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492707192,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492707192,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226545428,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226545428,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286043440,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286043440,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272706742,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272706742,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581268272,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268272,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214928,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214928,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581259472,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259472,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void list_lru_destroy(struct list_lru * lru)
```

```json
{
  "name": "list_lru_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581324176,
      "name": "list_lru_destroy",
      "external": true,
      "loc": "mm/list_lru.c:640",
      "file": "mm/list_lru.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:deactivate_locked_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324176,
      "name": "list_lru_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
