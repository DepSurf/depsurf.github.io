# Function: <code>tcf_chain0_head_change_cb_del</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588274400,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:704",
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
      "addr": 18446744071588274400,
      "name": "tcf_chain0_head_change_cb_del.isra.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588665968,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:927",
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
      "addr": 18446744071588665968,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588888928,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446744071588888928,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589771632,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:802",
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
      "addr": 18446744071589771632,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806432,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:804",
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
      "addr": 18446744071589806432,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711024,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:804",
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
      "addr": 18446744071589711024,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590469216,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:805",
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
      "addr": 18446744071590469216,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592072288,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:822",
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
      "addr": 18446744071592072288,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593892368,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:824",
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
      "addr": 18446744071593892368,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594267728,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:929",
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
      "addr": 18446744071594267728,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595065696,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:929",
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
      "addr": 18446744071595065696,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502478952,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446603336502478952,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235191892,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 3235191892,
      "name": "tcf_chain0_head_change_cb_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296038848,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 13835058055296038848,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278659376,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446743936278659376,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588495312,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446744071588495312,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588207312,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446744071588207312,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588827488,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446744071588827488,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain0_head_change_cb_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588970192,
      "name": "tcf_chain0_head_change_cb_del",
      "external": false,
      "loc": "net/sched/cls_api.c:839",
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
      "addr": 18446744071588970192,
      "name": "tcf_chain0_head_change_cb_del.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void tcf_chain0_head_change_cb_del(struct tcf_block * block, struct tcf_block_ext_info * ei)
```
</details>
</li>
</ul>
