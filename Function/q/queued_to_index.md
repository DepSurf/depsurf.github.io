# Function: <code>queued_to_index</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583184462,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:807",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583242820,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:849",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583421371,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:961",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583632987,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:959",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583735031,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1033",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583923362,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1032",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026654,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int queued_to_index(unsigned int queued)
```

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408320,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1047",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408320,
      "name": "queued_to_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584539326,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1097",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584570947,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1055",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584983426,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1061",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495858868,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229206532,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290056196,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274985844,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583995390,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583931246,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583979150,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
  "name": "queued_to_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584081390,
      "name": "queued_to_index",
      "external": false,
      "loc": "block/blk-mq.c:1048",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int queued_to_index(unsigned int queued)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
unsigned int queued_to_index(unsigned int queued)
```
</details>
</li>
</ul>
