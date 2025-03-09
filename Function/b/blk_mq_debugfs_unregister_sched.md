# Function: <code>blk_mq_debugfs_unregister_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583409219,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:948",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409264,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588803,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:949",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588848,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583805683,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:975",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805728,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888066,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:1014",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888112,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078544,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078544,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201248,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201248,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596400,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:940",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596400,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715344,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715344,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743504,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:934",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743504,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171568,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:935",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171568,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585907824,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:793",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907824,
      "name": "blk_mq_debugfs_unregister_sched",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696784,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:793",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696784,
      "name": "blk_mq_debugfs_unregister_sched",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957296,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:767",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957296,
      "name": "blk_mq_debugfs_unregister_sched",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237552,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:748",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237552,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496070768,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496070768,
      "name": "blk_mq_debugfs_unregister_sched",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229398704,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229398704,
      "name": "blk_mq_debugfs_unregister_sched",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290309472,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290309472,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275143758,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275143758,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169984,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169984,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105232,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105232,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153744,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153744,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258128,
      "name": "blk_mq_debugfs_unregister_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:936",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_exit_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258128,
      "name": "blk_mq_debugfs_unregister_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue * q)
```
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
