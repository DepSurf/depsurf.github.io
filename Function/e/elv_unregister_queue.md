# Function: <code>elv_unregister_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582725168,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:816",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582725168,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002928,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:815",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002928,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107904,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:813",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107904,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165183,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:874",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165008,
      "name": "elv_unregister_queue.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583165088,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583339983,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:891",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339808,
      "name": "elv_unregister_queue.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583339888,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583551615,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:861",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547744,
      "name": "elv_unregister_queue.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583552112,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670912,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:495",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670912,
      "name": "elv_unregister_queue.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583672880,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859552,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:496",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859552,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583861488,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583962208,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962208,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583964192,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584352355,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584352240,
      "name": "elv_unregister_queue",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468991,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:507",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468880,
      "name": "elv_unregister_queue",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584503951,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:507",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503840,
      "name": "elv_unregister_queue",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914543,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:515",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914448,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585615728,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:520",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615728,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385200,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:488",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385200,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631568,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:488",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631568,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902464,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:488",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902464,
      "name": "elv_unregister_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495785072,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495785072,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336495787520,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229136832,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229136832,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3229138176,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289963520,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289963520,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055289965888,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274927680,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274927680,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446743936274929906,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930944,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930944,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583932928,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583867888,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867888,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583869872,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914704,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914704,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583916688,
      "name": "elv_unregister_queue",
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
void elv_unregister_queue(struct request_queue * q)
```

```json
{
  "name": "elv_unregister_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584016704,
      "name": "elv_unregister_queue",
      "external": true,
      "loc": "block/elevator.c:516",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016704,
      "name": "elv_unregister_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071584018064,
      "name": "elv_unregister_queue",
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
