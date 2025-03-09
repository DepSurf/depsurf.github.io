# Function: <code>init_tio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585803910,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm.c:1872",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_mq_queue_rq"
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586245696,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:540",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586245696,
      "name": "init_tio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586450544,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:549",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586450544,
      "name": "init_tio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586557072,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:450",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557072,
      "name": "init_tio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024576,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:446",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024576,
      "name": "init_tio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```

```json
{
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587323008,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:451",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323008,
      "name": "init_tio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587503172,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:341",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587777158,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587982351,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588836565,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:353",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588852853,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:354",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588739941,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:354",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589430430,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:354",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590908334,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:335",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592604894,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:336",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593035454,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:338",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593786830,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:338",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501226564,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233730608,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294754352,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277921420,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587613327,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587381343,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587938495,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
  "name": "init_tio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588053775,
      "name": "init_tio",
      "external": false,
      "loc": "drivers/md/dm-rq.c:360",
      "file": "drivers/md/dm-rq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
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
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void init_tio(struct dm_rq_target_io * tio, struct request * rq, struct mapped_device * md)
```
</details>
</li>
</ul>
