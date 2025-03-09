# Function: <code>blk_freeze_queue_start</code>

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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583239216,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:86",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
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
      "addr": 18446744071583239216,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414832,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:122",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_freeze_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414832,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583623488,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_freeze_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623488,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728224,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:143",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728224,
      "name": "blk_freeze_queue_start",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919328,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:145",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919328,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584022624,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022624,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417072,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:131",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417072,
      "name": "blk_freeze_queue_start",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532816,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:135",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532816,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564000,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:135",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564000,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974960,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:135",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974960,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681536,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:164",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681536,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586459648,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:164",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_start_drain",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459648,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586702912,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:123",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_start_drain",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702912,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586974944,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:123",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_start_drain",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974944,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495853520,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495853520,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229202700,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229202700,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290051344,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290051344,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274981838,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274981838,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991360,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/nvme/host/core.c:nvme_start_freeze",
        "drivers/nvme/host/multipath.c:nvme_mpath_start_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991360,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927216,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend",
        "drivers/nvdimm/pmem.c:pmem_pagemap_kill",
        "drivers/nvme/host/core.c:nvme_start_freeze",
        "drivers/nvme/host/multipath.c:nvme_mpath_start_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927216,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975120,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975120,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074544,
      "name": "blk_freeze_queue_start",
      "external": true,
      "loc": "block/blk-mq.c:146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074544,
      "name": "blk_freeze_queue_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_freeze_queue_start(struct request_queue * q)
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
