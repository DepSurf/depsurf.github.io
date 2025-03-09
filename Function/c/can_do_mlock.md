# Function: <code>can_do_mlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580691504,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:27",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:SyS_mlockall"
      ],
      "caller_func": [
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:SyS_mlockall",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691504,
      "name": "can_do_mlock.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580691536,
      "name": "can_do_mlock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809674,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:27",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805072,
      "name": "can_do_mlock.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580805104,
      "name": "can_do_mlock",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580875050,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:27",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870128,
      "name": "can_do_mlock.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580870160,
      "name": "can_do_mlock",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919866,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:28",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915088,
      "name": "can_do_mlock.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580915120,
      "name": "can_do_mlock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581019498,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014464,
      "name": "can_do_mlock.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581014496,
      "name": "can_do_mlock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581154662,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148944,
      "name": "can_do_mlock.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581148976,
      "name": "can_do_mlock",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581233974,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228880,
      "name": "can_do_mlock.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581228912,
      "name": "can_do_mlock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581308234,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303040,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581303072,
      "name": "can_do_mlock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581366810,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361616,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581361648,
      "name": "can_do_mlock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581563716,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558592,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608966,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603520,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631622,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625984,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899462,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:30",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893456,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293682,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:40",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291728,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582788050,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:40",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784016,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005714,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:40",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583000720,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184866,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:40",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180096,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492772220,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__arm64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__arm64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492766536,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336492766568,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226590088,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226585668,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3226585700,
      "name": "can_do_mlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286138736,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286130912,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055286130976,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272748100,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272744218,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936272744254,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581335658,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330464,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581330496,
      "name": "can_do_mlock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581279370,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274192,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581274224,
      "name": "can_do_mlock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581326858,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321664,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581321696,
      "name": "can_do_mlock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_do_mlock()
```

```json
{
  "name": "can_do_mlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581390826,
      "name": "can_do_mlock",
      "external": true,
      "loc": "mm/mlock.c:29",
      "file": "mm/mlock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock"
      ],
      "caller_func": [
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385632,
      "name": "can_do_mlock.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581385664,
      "name": "can_do_mlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
