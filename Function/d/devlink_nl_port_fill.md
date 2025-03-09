# Function: <code>devlink_nl_port_fill</code>

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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:547",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596576,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071588619081,
      "name": "devlink_nl_port_fill.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588816064,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588816064,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589701424,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:566",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589701424,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:758",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748592,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    },
    {
      "addr": 18446744071591632795,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:832",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589617040,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071591576118,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:977",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590382752,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071592708650,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:1195",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591953200,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071594594660,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:1428",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593774544,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1653
    },
    {
      "addr": 18446744071596331627,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/devlink/leftover.c:895",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_port_new_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_port_get_dump_one",
        "net/devlink/leftover.c:devlink_nl_cmd_port_get_doit",
        "net/devlink/leftover.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595870608,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
    },
    {
      "addr": 18446744071596893597,
      "name": "devlink_nl_port_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596697504,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/devlink/port.c:446",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_nl_port_new_doit",
        "net/devlink/port.c:devlink_nl_port_get_dump_one",
        "net/devlink/port.c:devlink_nl_port_get_doit",
        "net/devlink/port.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596697504,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502388048,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502388048,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235125776,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235125776,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295924320,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295924320,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278601048,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278601048,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422448,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422448,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588135136,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588135136,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588754624,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754624,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_port_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895152,
      "name": "devlink_nl_port_fill",
      "external": false,
      "loc": "net/core/devlink.c:549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_port_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895152,
      "name": "devlink_nl_port_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
int devlink_nl_port_fill(struct sk_buff * msg, struct devlink * devlink, struct devlink_port * devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
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
<code>msg, devlink, devlink_port, cmd, portid, seq, flags, extack</code> ➡️ <code>msg, devlink_port, cmd, portid, seq, flags, extack</code>
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
