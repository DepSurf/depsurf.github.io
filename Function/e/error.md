# Function: <code>error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594944855,
      "name": "error",
      "external": false,
      "loc": "init/do_mounts_rd.c:338",
      "file": "init/do_mounts_rd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594949325,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:46",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594944855,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071594949325,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 23
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595108625,
      "name": "error",
      "external": false,
      "loc": "init/do_mounts_rd.c:331",
      "file": "init/do_mounts_rd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595113066,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:46",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595108625,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071595113066,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 23
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595356287,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:46",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595356287,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 23
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596274097,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:47",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:flush_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596274097,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602590126,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:48",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:flush_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602590126,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602758498,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:48",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602758498,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604552613,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604552613,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604646902,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604646902,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604659163,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604659163,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609010412,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:39",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609010412,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612072481,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:42",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612072481,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614210692,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:44",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614210692,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615129410,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:45",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615129410,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616891484,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:56",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616891484,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 34
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627487303,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:56",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627483648,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 42
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619231335,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:57",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619227568,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 42
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621521365,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:57",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621517456,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 42
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510809448,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510809448,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 52
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243255260,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243255260,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 44
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302372768,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302372768,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 44
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270606700,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270606700,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604585435,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604585435,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604577112,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604577112,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604663259,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604663259,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
void error(char * x)
```

```json
{
  "name": "error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604663264,
      "name": "error",
      "external": false,
      "loc": "init/initramfs.c:38",
      "file": "init/initramfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:flush_buffer",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_copy",
        "init/initramfs.c:do_reset",
        "init/initramfs.c:do_header",
        "init/initramfs.c:do_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604663264,
      "name": "error",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 28
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
