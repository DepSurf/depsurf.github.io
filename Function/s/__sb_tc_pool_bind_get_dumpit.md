# Function: <code>__sb_tc_pool_bind_get_dumpit</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588602526,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1402",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588825758,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sb_tc_pool_bind_get_dumpit(struct sk_buff * msg, int start, int * p_idx, struct devlink * devlink, struct devlink_sb * devlink_sb, u32 portid, u32 seq)
```

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589700720,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1431",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589700720,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int __sb_tc_pool_bind_get_dumpit(struct sk_buff * msg, int start, int * p_idx, struct devlink * devlink, struct devlink_sb * devlink_sb, u32 portid, u32 seq)
```

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733024,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1750",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733024,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589612388,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1953",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590364431,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:2488",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591987953,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:3007",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593797766,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:3277",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595854711,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/devlink/leftover.c:2627",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_dump_one"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596706411,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/devlink/sb.c:760",
      "file": "net/devlink/sb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_dump_one"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502399104,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235135444,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295934348,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278610758,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432142,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588144830,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588764318,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
  "name": "__sb_tc_pool_bind_get_dumpit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588904846,
      "name": "__sb_tc_pool_bind_get_dumpit",
      "external": false,
      "loc": "net/core/devlink.c:1404",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __sb_tc_pool_bind_get_dumpit(struct sk_buff * msg, int start, int * p_idx, struct devlink * devlink, struct devlink_sb * devlink_sb, u32 portid, u32 seq)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __sb_tc_pool_bind_get_dumpit(struct sk_buff * msg, int start, int * p_idx, struct devlink * devlink, struct devlink_sb * devlink_sb, u32 portid, u32 seq)
```
</details>
</li>
</ul>
