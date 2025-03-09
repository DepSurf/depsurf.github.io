# Function: <code>handle_bad_sector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582737156,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:1838",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:generic_make_request_checks"
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
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583019330,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:1803",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:generic_make_request_checks"
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
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583123769,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:1777",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:generic_make_request_checks"
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
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583188524,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:1923",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:generic_make_request_checks"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void handle_bad_sector(struct bio * bio)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353664,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:2021",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353664,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585796,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:2118",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585796,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694516,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:746",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694516,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583883012,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:733",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883012,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986212,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986212,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584375194,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:797",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375194,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478176,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:650",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478176,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584515711,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:651",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_checks"
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
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584926806,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:649",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_checks"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495812104,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495812104,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229163076,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229163076,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289998412,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289998412,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274948736,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274948736,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954948,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954948,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583891876,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891876,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938708,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938708,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```

```json
{
  "name": "handle_bad_sector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584040708,
      "name": "handle_bad_sector",
      "external": false,
      "loc": "block/blk-core.c:741",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040708,
      "name": "handle_bad_sector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void handle_bad_sector(struct bio * bio)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>sector_t maxsector</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void handle_bad_sector(struct bio * bio, sector_t maxsector)
```
</details>
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
