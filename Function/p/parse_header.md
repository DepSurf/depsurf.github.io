# Function: <code>parse_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594950050,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:162",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071595219922,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594950050,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071595219922,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595113798,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:162",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071595397131,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595113798,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071595397131,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595357295,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:162",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071595646820,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595357295,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071595646820,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596275098,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:163",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596740669,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275098,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071596740669,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602591130,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:164",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603074115,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602591130,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071603074115,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602761608,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:164",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071603248229,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602761608,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071603248229,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604555739,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605059485,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:55",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604555739,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605059485,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604650029,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605177239,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604650029,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605177239,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604662301,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605217817,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604662301,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605217817,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609011436,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:155",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071609305054,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609011436,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071609305054,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612073649,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:157",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071612374450,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612073649,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071612374450,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614211874,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:169",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071614515652,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614211874,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071614515652,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615130618,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:170",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071615465079,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615130618,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071615465079,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616894446,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:192",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071617266258,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616894446,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071617266258,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627485360,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:192",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071628239614,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/decompress_unlzo.c:unlzo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627485360,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071628239136,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619229392,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:186",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071620008846,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/decompress_unlzo.c:unlzo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619229392,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071620008368,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621519328,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:186",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071622321726,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/decompress_unlzo.c:unlzo"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621519328,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071622321248,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 299
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510812776,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446603336511355952,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510812776,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446603336511355952,
      "name": "parse_header",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243258916,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_header"
      ],
      "caller_func": []
    },
    {
      "addr": 3244020092,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3244020092,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302377208,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 13835058055302916180,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302377208,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 13835058055302916180,
      "name": "parse_header",
      "section": ".init.text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270609742,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446743936270886762,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270609742,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446743936270886762,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 216
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604588573,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605106461,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604588573,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605106461,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604580250,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605074539,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604580250,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605074539,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604666397,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605194855,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604666397,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605194855,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void parse_header(char * s)
```

```json
{
  "name": "parse_header",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604666402,
      "name": "parse_header",
      "external": false,
      "loc": "init/initramfs.c:154",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_header"
      ]
    },
    {
      "addr": 18446744071605222027,
      "name": "parse_header",
      "external": true,
      "loc": "lib/decompress_unlzo.c:41",
      "file": "lib/decompress_unlzo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604666402,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071605222027,
      "name": "parse_header",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
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
