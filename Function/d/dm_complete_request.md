# Function: <code>dm_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585796296,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm.c:1334",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:end_clone_request",
        "drivers/md/dm.c:map_request",
        "drivers/md/dm.c:map_request",
        "drivers/md/dm.c:dm_request_fn"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dm_complete_request(struct request * rq, int error)
```

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586245808,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:416",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586245808,
      "name": "dm_complete_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void dm_complete_request(struct request * rq, int error)
```

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586450656,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:425",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586450656,
      "name": "dm_complete_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void dm_complete_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556880,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:361",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556880,
      "name": "dm_complete_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void dm_complete_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024384,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:357",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024384,
      "name": "dm_complete_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void dm_complete_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322816,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:361",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322816,
      "name": "dm_complete_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587503322,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:267",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587777359,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587982147,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588836355,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:279",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588852647,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:279",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588739735,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:279",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589430231,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:279",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590907841,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:275",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592604261,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:274",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593034822,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:276",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593786198,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:276",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501226332,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233730268,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294754080,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277921182,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587613123,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587381139,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587938291,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
  "name": "dm_complete_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588053578,
      "name": "dm_complete_request",
      "external": false,
      "loc": "drivers/md/dm-rq.c:286",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dm_complete_request(struct request * rq, int error)
```
</details>
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
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void dm_complete_request(struct request * rq, blk_status_t error)
```
</details>
</li>
</ul>
