# Function: <code>elv_rqhash_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582726896,
      "name": "elv_rqhash_find",
      "external": false,
      "loc": "block/elevator.c:272",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/elevator.c:__elv_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726896,
      "name": "elv_rqhash_find.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005024,
      "name": "elv_rqhash_find",
      "external": false,
      "loc": "block/elevator.c:272",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005024,
      "name": "elv_rqhash_find.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110032,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:272",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110032,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165984,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:298",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165984,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340800,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:315",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340800,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549008,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:284",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549008,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671872,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:219",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671872,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860512,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:220",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860512,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963200,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963200,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584351152,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351152,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467792,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:229",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467792,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502752,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:229",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502752,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913280,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:229",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913280,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585614352,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:234",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614352,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586383696,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:202",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383696,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630064,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:202",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630064,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900960,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:202",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900960,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495786256,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495786256,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229137076,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229137076,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289964112,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289964112,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274928928,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274928928,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931936,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931936,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868880,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868880,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915696,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915696,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```

```json
{
  "name": "elv_rqhash_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017072,
      "name": "elv_rqhash_find",
      "external": true,
      "loc": "block/elevator.c:230",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_attempt_insert_merge",
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017072,
      "name": "elv_rqhash_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct request * elv_rqhash_find(struct request_queue * q, sector_t offset)
```
</details>
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
