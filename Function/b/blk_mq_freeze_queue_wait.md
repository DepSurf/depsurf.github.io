# Function: <code>blk_mq_freeze_queue_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582791056,
      "name": "blk_mq_freeze_queue_wait",
      "external": false,
      "loc": "block/blk-mq.c:93",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791056,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583068256,
      "name": "blk_mq_freeze_queue_wait",
      "external": false,
      "loc": "block/blk-mq.c:93",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068256,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583175936,
      "name": "blk_mq_freeze_queue_wait",
      "external": false,
      "loc": "block/blk-mq.c:75",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_queue_reinit_work",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175936,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231504,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:98",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231504,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408800,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:135",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_freeze_queue",
        "block/blk-mq.c:blk_freeze_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408800,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619360,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:150",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_freeze_queue",
        "block/blk-mq.c:blk_freeze_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619360,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723952,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:156",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723952,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912176,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:159",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912176,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584015312,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015312,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584407600,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:145",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407600,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523472,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:149",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523472,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556048,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:149",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556048,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967344,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:149",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:del_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967344,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670944,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:178",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/genhd.c:del_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670944,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586446896,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:178",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/genhd.c:del_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446896,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586693904,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/genhd.c:del_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586693904,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965168,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/genhd.c:del_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965168,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495845400,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495845400,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229193504,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229193504,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290039024,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290039024,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274975324,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274975324,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984048,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "drivers/nvme/host/core.c:nvme_wait_freeze",
        "drivers/nvme/host/multipath.c:nvme_mpath_wait_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984048,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919904,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "drivers/nvme/host/core.c:nvme_wait_freeze",
        "drivers/nvme/host/multipath.c:nvme_mpath_wait_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919904,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583967808,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967808,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_freeze_queue_wait(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069824,
      "name": "blk_mq_freeze_queue_wait",
      "external": true,
      "loc": "block/blk-mq.c:160",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069824,
      "name": "blk_mq_freeze_queue_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
