# Function: <code>__blk_queue_bounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582863192,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:182",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583149075,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:182",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583260999,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:182",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583313256,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:192",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583496152,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:193",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583709941,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:198",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583818176,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008368,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008368,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1905
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111872,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111872,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584508432,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:288",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508432,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618672,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:287",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618672,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_queue_bounce",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229298832,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229298832,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2108
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584080608,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080608,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016368,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016368,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064368,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064368,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```

```json
{
  "name": "__blk_queue_bounce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166864,
      "name": "__blk_queue_bounce",
      "external": false,
      "loc": "block/bounce.c:286",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166864,
      "name": "__blk_queue_bounce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1974
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
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __blk_queue_bounce(struct request_queue * q, struct bio * * bio_orig, mempool_t * pool)
```
</details>
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
