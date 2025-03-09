# Function: <code>dm_requeue_original_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dm_requeue_original_request(struct mapped_device * md, struct request * rq)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798800,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm.c:1212",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_softirq_done",
        "drivers/md/dm.c:map_request",
        "drivers/md/dm.c:map_tio_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798800,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void dm_requeue_original_request(struct mapped_device * md, struct request * rq)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246768,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:334",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_tio_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246768,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586451616,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:342",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_tio_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451616,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586557264,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:268",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_tio_request",
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557264,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024768,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:263",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_tio_request",
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024768,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323200,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:263",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_tio_request",
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323200,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587502864,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:179",
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
      "addr": 18446744071587502864,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776832,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
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
      "addr": 18446744071587776832,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587981360,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981360,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835504,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835504,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588851856,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851856,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738944,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738944,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429440,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429440,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590907360,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:187",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590907360,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592603872,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:186",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592603872,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593034432,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593034432,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593785808,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:188",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593785808,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501225584,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501225584,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233729616,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233729616,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294753008,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294753008,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277920624,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277920624,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587612336,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612336,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587380352,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380352,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937504,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937504,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void dm_requeue_original_request(struct dm_rq_target_io * tio, bool delay_requeue)
```

```json
{
  "name": "dm_requeue_original_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588052768,
      "name": "dm_requeue_original_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:195",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588052768,
      "name": "dm_requeue_original_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
<b>Param added. </b>
<code>struct dm_rq_target_io * tio</code>
</li>
<li>
<b>Param added. </b>
<code>bool delay_requeue</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mapped_device * md</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request * rq</code>
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
