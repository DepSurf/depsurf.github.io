# Function: <code>zero_fill_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582716144,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:515",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582716144,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993088,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:514",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993088,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098032,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:518",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098032,
      "name": "zero_fill_bio",
      "section": ".text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154176,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:532",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154176,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329232,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:532",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329232,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585847021,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:529",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587307038,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:529",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583666833,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:478",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978944,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:478",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587487150,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:478",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583855837,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:474",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586225325,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:474",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587760757,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:474",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583957877,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586373553,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587965237,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584392398,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:465",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587132871,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:465",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588818885,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:465",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584506533,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:476",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217911,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:476",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588835557,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:476",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494176,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:496",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494176,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902736,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:529",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902736,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602912,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:585",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602912,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586371920,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:610",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371920,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void zero_fill_bio(struct bio * bio)
```

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618608,
      "name": "zero_fill_bio",
      "external": true,
      "loc": "block/bio.c:609",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618608,
      "name": "zero_fill_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947921,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:503",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226795,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:503",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593765857,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:503",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495779540,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499213592,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501207328,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229131660,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 3231749168,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 3233711528,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289955240,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292427216,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294728816,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274923854,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276506244,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277905676,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583926613,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586135441,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587596213,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583863557,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585980049,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364293,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583910373,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586321521,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587921381,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
  "name": "zero_fill_bio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011669,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433078,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588036645,
      "name": "zero_fill_bio",
      "external": false,
      "loc": "include/linux/bio.h:475",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:endio"
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void zero_fill_bio(struct bio * bio)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void zero_fill_bio(struct bio * bio)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void zero_fill_bio(struct bio * bio)
```
</details>
</li>
</ul>
