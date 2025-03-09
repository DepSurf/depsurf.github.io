# Function: <code>scsi_run_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584797600,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:486",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584797600,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585157840,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:452",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157840,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351664,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:461",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351664,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437760,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:490",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_device_resume",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437760,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868384,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:515",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868384,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586114512,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:528",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114512,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260800,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:517",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260800,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586504880,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586504880,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652768,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652768,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449344,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:494",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449344,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587517408,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:479",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517408,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398784,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:446",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398784,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970496,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:451",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970496,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589326240,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:452",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326240,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590892528,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:448",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892528,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591235952,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:446",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235952,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591583200,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:444",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_unblock_requests",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591583200,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499557272,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499557272,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232014328,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232014328,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292844320,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292844320,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276750208,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276750208,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586343248,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586343248,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184576,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184576,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600736,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600736,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
void scsi_run_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_run_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713008,
      "name": "scsi_run_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:514",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_run_host_queues",
        "drivers/scsi/scsi_lib.c:scsi_requeue_run_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713008,
      "name": "scsi_run_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
