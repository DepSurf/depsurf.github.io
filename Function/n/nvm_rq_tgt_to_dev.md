# Function: <code>nvm_rq_tgt_to_dev</code>

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
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970688,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:486",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_submit_io",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970688,
      "name": "nvm_rq_tgt_to_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392048,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:507",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392048,
      "name": "nvm_rq_tgt_to_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635408,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:599",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635408,
      "name": "nvm_rq_tgt_to_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585765166,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:604",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997264,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:606",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586144432,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586901542,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:610",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586986406,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:606",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586868085,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:606",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498935212,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231509260,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292073984,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276322776,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904800,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586094448,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
  "name": "nvm_rq_tgt_to_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586203056,
      "name": "nvm_rq_tgt_to_dev",
      "external": false,
      "loc": "drivers/lightnvm/core.c:611",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io"
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
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void nvm_rq_tgt_to_dev(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```
</details>
</li>
</ul>
