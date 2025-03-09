# Function: <code>scr_memmovew</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void scr_memmovew(u16 * d, const u16 * s, unsigned int count)
```

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583426258,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584052896,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:scrup"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:scrdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052896,
      "name": "scr_memmovew",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void scr_memmovew(u16 * d, const u16 * s, unsigned int count)
```

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583746322,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584391651,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:scrup"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:scrdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384304,
      "name": "scr_memmovew",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583884454,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584574323,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583933350,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584655993,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:45",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584195958,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585067086,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584416047,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585301283,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584512475,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585422110,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584711479,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585636512,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584847575,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585777808,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585543500,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586504352,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585677775,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586616415,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585558751,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586500689,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586029411,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587033121,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246699,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335985,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588485611,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589756479,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588765275,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590061343,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589068491,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590400511,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498495732,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231149800,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275782238,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276119224,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798759,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585538800,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584729543,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585408624,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584800183,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585728208,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scr_memmovew",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584905319,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585836224,
      "name": "scr_memmovew",
      "external": false,
      "loc": "include/linux/vt_buffer.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void scr_memmovew(u16 * d, const u16 * s, unsigned int count)
```
</details>
</li>
</ul>
