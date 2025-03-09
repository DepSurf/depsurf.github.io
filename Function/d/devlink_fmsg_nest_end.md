# Function: <code>devlink_fmsg_nest_end</code>

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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588605780,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4117",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588830404,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589707893,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4612",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589719338,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:5301",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589579264,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589579264,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592707287,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:6117",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_fmsg_obj_nest_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328016,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071592707110,
      "name": "devlink_fmsg_nest_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594593911,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:6612",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_fmsg_pair_nest_end",
        "net/core/devlink.c:devlink_fmsg_obj_nest_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591916880,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071594593784,
      "name": "devlink_fmsg_nest_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596330592,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:7167",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_fmsg_pair_nest_end",
        "net/core/devlink.c:devlink_fmsg_obj_nest_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593721952,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071596330465,
      "name": "devlink_fmsg_nest_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596894177,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/devlink/health.c:684",
      "file": "net/devlink/health.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_fmsg_pair_nest_end",
        "net/devlink/health.c:devlink_fmsg_obj_nest_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595908800,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071596893945,
      "name": "devlink_fmsg_nest_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596753696,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/devlink/health.c:707",
      "file": "net/devlink/health.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit",
        "net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit",
        "net/devlink/health.c:devlink_fmsg_binary_pair_put",
        "net/devlink/health.c:devlink_fmsg_binary_pair_put",
        "net/devlink/health.c:devlink_fmsg_binary_pair_put",
        "net/devlink/health.c:devlink_fmsg_binary_pair_put",
        "net/devlink/health.c:devlink_fmsg_string_pair_put",
        "net/devlink/health.c:devlink_fmsg_string_pair_put",
        "net/devlink/health.c:devlink_fmsg_u64_pair_put",
        "net/devlink/health.c:devlink_fmsg_u64_pair_put",
        "net/devlink/health.c:devlink_fmsg_u32_pair_put",
        "net/devlink/health.c:devlink_fmsg_u32_pair_put",
        "net/devlink/health.c:devlink_fmsg_u8_pair_put",
        "net/devlink/health.c:devlink_fmsg_u8_pair_put",
        "net/devlink/health.c:devlink_fmsg_bool_pair_put",
        "net/devlink/health.c:devlink_fmsg_bool_pair_put",
        "net/devlink/health.c:devlink_health_do_dump",
        "net/devlink/health.c:devlink_health_do_dump"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502404528,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235140344,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```

```json
{
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295903152,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295903152,
      "name": "devlink_fmsg_nest_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278593402,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588436788,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588149476,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588768964,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
  "name": "devlink_fmsg_nest_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588909492,
      "name": "devlink_fmsg_nest_end",
      "external": false,
      "loc": "net/core/devlink.c:4171",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int devlink_fmsg_nest_end(struct devlink_fmsg * fmsg)
```
</details>
</li>
</ul>
