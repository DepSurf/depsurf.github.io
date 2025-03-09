# Function: <code>cdev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011952,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:335",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011952,
      "name": "cdev_put",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170352,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:339",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170352,
      "name": "cdev_put",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247328,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:339",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247328,
      "name": "cdev_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293979,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:339",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293840,
      "name": "cdev_put.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581295376,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433643,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:364",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433504,
      "name": "cdev_put.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581435216,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581592939,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:364",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591536,
      "name": "cdev_put.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581593424,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678933,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:364",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678592,
      "name": "cdev_put.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581679408,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796965,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796624,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581797440,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581869589,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869248,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581870064,
      "name": "cdev_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582095676,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096224,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582142492,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143040,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582167276,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167872,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582484476,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485120,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005470,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006128,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583567422,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568320,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583783518,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784432,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989097,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990016,
      "name": "cdev_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493342376,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493341880,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336493343008,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226935360,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226935192,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3226935856,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286884160,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286883888,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055286887408,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273072090,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273071610,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936273072562,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581838325,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837984,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581838800,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775989,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775648,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581776464,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829637,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829296,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581830112,
      "name": "cdev_put",
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
void cdev_put(struct cdev * p)
```

```json
{
  "name": "cdev_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581898782,
      "name": "cdev_put",
      "external": true,
      "loc": "fs/char_dev.c:361",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898656,
      "name": "cdev_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581899280,
      "name": "cdev_put",
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
