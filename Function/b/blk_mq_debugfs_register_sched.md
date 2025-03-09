# Function: <code>blk_mq_debugfs_register_sched</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409120,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:923",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409120,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588704,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:924",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588704,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583805584,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:950",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805584,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583887952,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:989",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887952,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078432,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078432,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201136,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201136,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596304,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:921",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596304,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715248,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715248,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743408,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:915",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743408,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171472,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:916",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171472,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585907632,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:772",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907632,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696576,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:772",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696576,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957088,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:746",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957088,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237344,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:727",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237344,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496070664,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496070664,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229398600,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229398600,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290309296,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290309296,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275143662,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275143662,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169872,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169872,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105120,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105120,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153632,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153632,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_debugfs_register_sched(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_register_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258016,
      "name": "blk_mq_debugfs_register_sched",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:917",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258016,
      "name": "blk_mq_debugfs_register_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int blk_mq_debugfs_register_sched(struct request_queue * q)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
