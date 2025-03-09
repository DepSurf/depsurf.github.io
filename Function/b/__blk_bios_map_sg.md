# Function: <code>__blk_bios_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582777136,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:378",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583055796,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:405",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583163711,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:416",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583219220,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:406",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583395489,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:407",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583607091,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:416",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583712517,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:458",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_rq_map_sg"
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583899248,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:409",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899248,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002528,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002528,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395536,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:472",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395536,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510528,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:488",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510528,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544128,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:487",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544128,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584955440,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:489",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584955440,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585659488,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:489",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659488,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586434560,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:526",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586434560,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1053
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586681728,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:527",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681728,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586953040,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:523",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953040,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495832288,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495832288,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229180408,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229180408,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290022656,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290022656,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274964854,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274964854,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971264,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971264,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583908160,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908160,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955024,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955024,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "__blk_bios_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057008,
      "name": "__blk_bios_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057008,
      "name": "__blk_bios_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
int __blk_bios_map_sg(struct request_queue * q, struct bio * bio, struct scatterlist * sglist, struct scatterlist * * sg)
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
