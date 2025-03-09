# Function: <code>blk_mq_debugfs_unregister</code>

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
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583409617,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:839",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408432,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583589224,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:840",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588016,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583806104,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:866",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804896,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888835,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:905",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887264,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584077872,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077872,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200576,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200576,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595696,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:861",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595696,
      "name": "blk_mq_debugfs_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714672,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:859",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714672,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742832,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742832,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170896,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:858",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170896,
      "name": "blk_mq_debugfs_unregister",
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
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496070080,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496070080,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229398064,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229398064,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290308464,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290308464,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275143156,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275143156,
      "name": "blk_mq_debugfs_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169312,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169312,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104560,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104560,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153072,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153072,
      "name": "blk_mq_debugfs_unregister",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
```

```json
{
  "name": "blk_mq_debugfs_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584257456,
      "name": "blk_mq_debugfs_unregister",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:857",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257456,
      "name": "blk_mq_debugfs_unregister",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue * q)
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
