# Function: <code>__blk_mq_put_driver_tag</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_put_driver_tag(struct blk_mq_hw_ctx * hctx, struct request * rq)
```

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233648,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.c:889",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233648,
      "name": "__blk_mq_put_driver_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583385658,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:159",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419076,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:159",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583595641,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:174",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632903,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:174",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583701722,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:215",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734935,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:215",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583890465,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:208",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923262,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:208",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583993720,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584026554,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584382632,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:199",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424143,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:199",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584496588,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:225",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584540008,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:225",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584531276,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:243",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571721,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:243",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584942060,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:245",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584984275,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:245",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585644522,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:251",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585696638,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:251",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586416746,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:252",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476140,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:252",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586664106,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:302",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586726301,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:302",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586935222,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:334",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586997435,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:334",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495820532,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495859532,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229170696,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3229206392,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290010316,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290056096,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274956374,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274986430,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583962456,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995290,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583899368,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583931146,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583946216,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583979050,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
  "name": "__blk_mq_put_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584048200,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584081290,
      "name": "__blk_mq_put_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:209",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __blk_mq_put_driver_tag(struct blk_mq_hw_ctx * hctx, struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __blk_mq_put_driver_tag(struct blk_mq_hw_ctx * hctx, struct request * rq)
```
</details>
</li>
</ul>
