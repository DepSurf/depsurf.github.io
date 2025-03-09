# Function: <code>blk_mq_sched_free_requests</code>

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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946384,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:553",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946384,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049952,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049952,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584446429,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:648",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445888,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562690,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:617",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562128,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595598,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:619",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595040,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585010378,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:659",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009728,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495886888,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495886888,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229231468,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229231468,
      "name": "blk_mq_sched_free_requests",
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290091520,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290091520,
      "name": "blk_mq_sched_free_requests",
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275007702,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275007702,
      "name": "blk_mq_sched_free_requests",
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018688,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018688,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954496,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954496,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002448,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002448,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
```

```json
{
  "name": "blk_mq_sched_free_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104864,
      "name": "blk_mq_sched_free_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:583",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104864,
      "name": "blk_mq_sched_free_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_sched_free_requests(struct request_queue * q)
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
void blk_mq_sched_free_requests(struct request_queue * q)
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
