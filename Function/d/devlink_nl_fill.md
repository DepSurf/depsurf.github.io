# Function: <code>devlink_nl_fill</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:467",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588606816,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071588619464,
      "name": "devlink_nl_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814784,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814784,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697232,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:478",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697232,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589752288,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:603",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752288,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589634048,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:606",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634048,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590387632,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:703",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590387632,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591975728,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:920",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591975728,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593786928,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:1096",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593786928,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595898896,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/devlink/dev.c:141",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_nl_cmd_get_dump_one",
        "net/devlink/dev.c:devlink_nl_cmd_get_doit",
        "net/devlink/dev.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595898896,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596682912,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/devlink/dev.c:159",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_nl_get_dump_one",
        "net/devlink/dev.c:devlink_nl_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596682912,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502386696,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502386696,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235122224,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235122224,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295929472,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295929472,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278603222,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278603222,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421168,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421168,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588133856,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588133856,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753344,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753344,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893872,
      "name": "devlink_nl_fill",
      "external": false,
      "loc": "net/core/devlink.c:462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893872,
      "name": "devlink_nl_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int devlink_nl_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
