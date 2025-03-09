# Function: <code>elevator_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582725890,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:894",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583003653,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:893",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583108629,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:891",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165120,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:990",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165120,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339920,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:1007",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339920,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551552,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:1016",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551552,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673120,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:638",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673120,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861760,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:637",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861760,
      "name": "elevator_switch",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964480,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964480,
      "name": "elevator_switch",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584352795,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change"
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
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584469403,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:703",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change"
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
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584504359,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:704",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change"
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
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584914935,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:722",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change"
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
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585616313,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:726",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385744,
      "name": "elevator_switch",
      "external": true,
      "loc": "block/elevator.c:657",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385744,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586632112,
      "name": "elevator_switch",
      "external": true,
      "loc": "block/elevator.c:660",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632112,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586903008,
      "name": "elevator_switch",
      "external": true,
      "loc": "block/elevator.c:660",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903008,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495787824,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495787824,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229138468,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229138468,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289966288,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289966288,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274930176,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274930176,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933216,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933216,
      "name": "elevator_switch",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870160,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870160,
      "name": "elevator_switch",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916976,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916976,
      "name": "elevator_switch",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```

```json
{
  "name": "elevator_switch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018352,
      "name": "elevator_switch",
      "external": false,
      "loc": "block/elevator.c:710",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elv_iosched_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018352,
      "name": "elevator_switch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int elevator_switch(struct request_queue * q, struct elevator_type * new_e)
```
</details>
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
