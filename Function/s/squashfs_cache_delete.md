# Function: <code>squashfs_cache_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127760,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127760,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217504,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217504,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582303477,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301552,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071582302944,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452597,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450672,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071582452064,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582643971,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641072,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582642624,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582745747,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:210",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742848,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582744400,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582919795,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916880,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582918432,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583026339,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023424,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583024976,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583344147,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341216,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583342784,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591351292,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457728,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583459248,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591294176,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480144,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583481216,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592275757,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834544,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583835616,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594057600,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402432,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071584403680,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585059301,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057520,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071585058832,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288482,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286720,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585288016,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585522219,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520336,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585521632,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494720960,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494718616,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446603336494720416,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228155604,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228153572,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 3228155124,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288542328,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288539168,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 13835058055288541648,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274069366,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274067146,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446743936274068870,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582995075,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992160,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582993712,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932227,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929312,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582930864,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582983683,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980768,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582982320,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```

```json
{
  "name": "squashfs_cache_delete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583072755,
      "name": "squashfs_cache_delete",
      "external": true,
      "loc": "fs/squashfs/cache.c:197",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_init"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_cache_init",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_put_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069856,
      "name": "squashfs_cache_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583071392,
      "name": "squashfs_cache_delete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void squashfs_cache_delete(struct squashfs_cache * cache)
```
</details>
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
