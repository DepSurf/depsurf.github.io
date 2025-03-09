# Function: <code>aio_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aio_complete(struct kiocb * kiocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319728,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1059",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_run_iocb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319728,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
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
void aio_complete(struct kiocb * kiocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487904,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1069",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_run_iocb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487904,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
void aio_complete(struct kiocb * kiocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567168,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1072",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567168,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
void aio_complete(struct kiocb * kiocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624832,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1077",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624832,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
void aio_complete(struct kiocb * kiocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769712,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1101",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769712,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
void aio_complete(struct aio_kiocb * iocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941680,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1055",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941680,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
void aio_complete(struct aio_kiocb * iocb, long int res, long int res2)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026768,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1093",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026768,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582168682,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582246074,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471920,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471920,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528976,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1090",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528976,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565056,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1087",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565056,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881920,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881920,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583438672,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1114",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438672,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028880,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1115",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028880,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253600,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1112",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253600,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470816,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1127",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470816,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493806696,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493806696,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227313384,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227313384,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287436628,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273388588,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273388588,
      "name": "aio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214810,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582151696,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582205290,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
  "name": "aio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582280242,
      "name": "aio_complete",
      "external": false,
      "loc": "fs/aio.c:1088",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw"
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aio_kiocb * iocb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb * kiocb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void aio_complete(struct aio_kiocb * iocb, long int res, long int res2)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void aio_complete(struct aio_kiocb * iocb)
```
</details>
</li>
</ul>
