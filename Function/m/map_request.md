# Function: <code>map_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801440,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm.c:1940",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:map_tio_request",
        "drivers/md/dm.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801440,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int map_request(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586248224,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:619",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248224,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586453024,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:628",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453024,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586557504,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:475",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557504,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025024,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:472",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025024,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:477",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323456,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    },
    {
      "addr": 18446744071587326641,
      "name": "map_request.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587503254,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:365",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587777233,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981520,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071587983773,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:377",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835728,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071588838208,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:378",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588852080,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071591593716,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:378",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588739168,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071591536851,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:378",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429664,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071592650703,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:359",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590907600,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071594535349,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592604128,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592604128,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593034688,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:362",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593034688,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593786064,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:362",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593786064,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501225752,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501225752,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233729768,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233729768,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294753232,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294753232,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277920782,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277920782,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612496,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071587614749,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380512,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071587382765,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937664,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071587939917,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```

```json
{
  "name": "map_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:384",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588052928,
      "name": "map_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071588055197,
      "name": "map_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request * rq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mapped_device * md</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int map_request(struct dm_rq_target_io * tio)
```
</details>
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
