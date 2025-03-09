# Function: <code>devlink_nl_health_reporter_fill</code>

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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4868",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589264,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071588618732,
      "name": "devlink_nl_health_reporter_fill.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588805584,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805584,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589694832,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:5246",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589694832,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589729264,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:6037",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729264,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589608400,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:6240",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589608400,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:6853",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590359504,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
    },
    {
      "addr": 18446744071592708006,
      "name": "devlink_nl_health_reporter_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:7345",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591941328,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071594594535,
      "name": "devlink_nl_health_reporter_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:7900",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593745744,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071596331243,
      "name": "devlink_nl_health_reporter_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/devlink/health.c:262",
      "file": "net/devlink/health.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595914480,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
    },
    {
      "addr": 18446744071596894495,
      "name": "devlink_nl_health_reporter_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/devlink/health.c:260",
      "file": "net/devlink/health.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/health.c:devlink_nl_health_reporter_get_dump_one",
        "net/devlink/health.c:devlink_nl_health_reporter_get_dump_one",
        "net/devlink/health.c:devlink_nl_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596749856,
      "name": "devlink_nl_health_reporter_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071597819497,
      "name": "devlink_nl_health_reporter_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502379224,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502379224,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235112756,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235112756,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295916128,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295916128,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278596072,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278596072,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588411968,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411968,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588124656,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124656,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588744144,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744144,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
  "name": "devlink_nl_health_reporter_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884672,
      "name": "devlink_nl_health_reporter_fill",
      "external": false,
      "loc": "net/core/devlink.c:4924",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884672,
      "name": "devlink_nl_health_reporter_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
int devlink_nl_health_reporter_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_health_reporter * reporter, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct devlink * devlink</code>
</li>
<li>
<b>Param reordered. </b>
<code>msg, devlink, reporter, cmd, portid, seq, flags</code> ➡️ <code>msg, reporter, cmd, portid, seq, flags</code>
</li>
</ul>
</details>
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
