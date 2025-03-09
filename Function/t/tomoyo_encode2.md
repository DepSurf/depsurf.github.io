# Function: <code>tomoyo_encode2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460208,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:21",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460208,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682448,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:21",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682448,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775504,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:21",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775504,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582868183,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:21",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867872,
      "name": "tomoyo_encode2.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071582868128,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025143,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024832,
      "name": "tomoyo_encode2.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583025088,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583225639,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225328,
      "name": "tomoyo_encode2.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583225584,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583342711,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342400,
      "name": "tomoyo_encode2.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583342656,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583530222,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583529904,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583530160,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583636110,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583635792,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583636048,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583993470,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993152,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071583993408,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113086,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112768,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071584113024,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140536,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140224,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071584140480,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584524328,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524016,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071584524272,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585162912,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162912,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585889088,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889088,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120976,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120976,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586370272,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:23",
      "file": "security/tomoyo/realpath.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370272,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495423964,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495423536,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446603336495423864,
      "name": "tomoyo_encode2",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228793568,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228793236,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 3228793492,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289462464,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289461968,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 13835058055289462384,
      "name": "tomoyo_encode2",
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274619292,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274618920,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446743936274619200,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583604846,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604528,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583604784,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541902,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541584,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583541840,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588622,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588304,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583588560,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
char * tomoyo_encode2(const char * str, int str_len)
```

```json
{
  "name": "tomoyo_encode2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583685710,
      "name": "tomoyo_encode2",
      "external": true,
      "loc": "security/tomoyo/realpath.c:22",
      "file": "security/tomoyo/realpath.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/tomoyo/realpath.c:tomoyo_encode"
      ],
      "caller_func": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/realpath.c:tomoyo_encode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685392,
      "name": "tomoyo_encode2.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071583685648,
      "name": "tomoyo_encode2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
