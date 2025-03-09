# Function: <code>__elevator_exit</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860368,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:181",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860368,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963056,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963056,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584352392,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350928,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584469028,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467568,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584503988,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502528,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914580,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913056,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495786056,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495786056,
      "name": "__elevator_exit",
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229136908,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229136908,
      "name": "__elevator_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289963872,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289963872,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274928752,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274928752,
      "name": "__elevator_exit",
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931792,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931792,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868736,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868736,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915552,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915552,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```

```json
{
  "name": "__elevator_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016928,
      "name": "__elevator_exit",
      "external": true,
      "loc": "block/elevator.c:191",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016928,
      "name": "__elevator_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __elevator_exit(struct request_queue * q, struct elevator_queue * e)
```
</details>
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
