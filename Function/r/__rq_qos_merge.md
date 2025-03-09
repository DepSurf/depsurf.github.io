# Function: <code>__rq_qos_merge</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109504,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109504,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504976,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge",
        "block/blk-core.c:bio_attempt_front_merge",
        "block/blk-core.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504976,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615440,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615440,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647040,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647040,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063968,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063968,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585786992,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786992,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586567376,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:80",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567376,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824752,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:80",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824752,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101840,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:80",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_discard_merge",
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101840,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495953000,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495953000,
      "name": "__rq_qos_merge",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229296272,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229296272,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290175280,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290175280,
      "name": "__rq_qos_merge",
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275062980,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275062980,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078240,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078240,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014000,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014000,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062000,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062000,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```

```json
{
  "name": "__rq_qos_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164496,
      "name": "__rq_qos_merge",
      "external": true,
      "loc": "block/blk-rq-qos.c:86",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_attempt_discard_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164496,
      "name": "__rq_qos_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __rq_qos_merge(struct rq_qos * rqos, struct request * rq, struct bio * bio)
```
</details>
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
