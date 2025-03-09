# Function: <code>tcf_block_owner_del</code>

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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum tcf_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095072,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:560",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095072,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum tcf_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272576,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1028",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272576,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588686995,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1406",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666192,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071588686995,
      "name": "tcf_block_owner_del.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588887088,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588887088,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589771856,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1283",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771856,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806656,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1284",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806656,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711248,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1284",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711248,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590469440,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1285",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590469440,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592072544,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1302",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072544,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593892640,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1304",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593892640,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594268000,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1409",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594268000,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595065984,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1411",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_put_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595065984,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502476224,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502476224,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235192144,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235192144,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296034976,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296034976,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278657454,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278657454,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588493472,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588493472,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588205472,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205472,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588825648,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825648,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum flow_block_binder_type binder_type)
```

```json
{
  "name": "tcf_block_owner_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966944,
      "name": "tcf_block_owner_del",
      "external": false,
      "loc": "net/sched/cls_api.c:1320",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966944,
      "name": "tcf_block_owner_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tcf_block_owner_del(struct tcf_block * block, struct Qdisc * q, enum tcf_block_binder_type binder_type)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum tcf_block_binder_type binder_type</code> ➡️ <code>enum flow_block_binder_type binder_type</code>
</li>
</ul>
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
