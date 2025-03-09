# Function: <code>part_in_flight_rw</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583661984,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:85",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661984,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768624,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:88",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768624,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958144,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958144,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061616,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061616,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584454581,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:131",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584570805,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:148",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603129,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:145",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585019003,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:159",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585736462,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:163",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586516387,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:140",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586763638,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:136",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
  "name": "part_in_flight_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587036118,
      "name": "part_in_flight_rw",
      "external": false,
      "loc": "block/genhd.c:136",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_inflight_show"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495903328,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495903328,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229246332,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229246332,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290110880,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290110880,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275018876,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275018876,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030352,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030352,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966144,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966144,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014112,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014112,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "part_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116640,
      "name": "part_in_flight_rw",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116640,
      "name": "part_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void part_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
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
