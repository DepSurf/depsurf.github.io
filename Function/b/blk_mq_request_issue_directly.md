# Function: <code>blk_mq_request_issue_directly</code>

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
blk_status_t blk_mq_request_issue_directly(struct request * rq)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634336,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1738",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634336,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928000,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1873",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928000,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031360,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031360,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426509,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1953",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426176,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584541690,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:2050",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541200,
      "name": "blk_mq_request_issue_directly",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573402,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:2074",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572912,
      "name": "blk_mq_request_issue_directly",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584986158,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:2085",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985600,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585693970,
      "name": "blk_mq_request_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2543",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
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
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586473208,
      "name": "blk_mq_request_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2686",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720400,
      "name": "blk_mq_request_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2663",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720400,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586991584,
      "name": "blk_mq_request_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2685",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586991584,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495864496,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495864496,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229211536,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229211536,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290063216,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290063216,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274990352,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274990352,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000096,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000096,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583935920,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935920,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983856,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983856,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```

```json
{
  "name": "blk_mq_request_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086272,
      "name": "blk_mq_request_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086272,
      "name": "blk_mq_request_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
blk_status_t blk_mq_request_issue_directly(struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
blk_status_t blk_mq_request_issue_directly(struct request * rq, bool last)
```
</details>
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
