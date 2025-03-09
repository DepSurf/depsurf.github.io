# Function: <code>elv_merged_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue * q, struct request * rq, int type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727728,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:497",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727728,
      "name": "elv_merged_request",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue * q, struct request * rq, int type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005456,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:496",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005456,
      "name": "elv_merged_request",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue * q, struct request * rq, int type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110464,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:494",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110464,
      "name": "elv_merged_request",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166624,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:522",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166624,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341440,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:539",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341440,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549648,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:508",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549648,
      "name": "elv_merged_request",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672464,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:379",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672464,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861088,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:380",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861088,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963776,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963776,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584351728,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351728,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468368,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:389",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468368,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503328,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:389",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503328,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913936,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:397",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913936,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585615120,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:402",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615120,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384512,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:370",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384512,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630880,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:370",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630880,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901776,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:370",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901776,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495786952,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495786952,
      "name": "elv_merged_request",
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229137720,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229137720,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289965120,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289965120,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274929462,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274929462,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932512,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932512,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869456,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869456,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916272,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916272,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void elv_merged_request(struct request_queue * q, struct request * rq, enum elv_merge type)
```

```json
{
  "name": "elv_merged_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017648,
      "name": "elv_merged_request",
      "external": true,
      "loc": "block/elevator.c:390",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017648,
      "name": "elv_merged_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum elv_merge type</code>
</li>
</ul>
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
