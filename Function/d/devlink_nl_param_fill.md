# Function: <code>devlink_nl_param_fill</code>

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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3001",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608912,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
    },
    {
      "addr": 18446744071588619532,
      "name": "devlink_nl_param_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831744,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071588841885,
      "name": "devlink_nl_param_fill.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589710544,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3166",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710544,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589740224,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3711",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589740224,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589625584,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3914",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589625584,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:4499",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590374896,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1412
    },
    {
      "addr": 18446744071592708234,
      "name": "devlink_nl_param_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:5029",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591962384,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1564
    },
    {
      "addr": 18446744071594594822,
      "name": "devlink_nl_param_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:5553",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593766144,
      "name": "devlink_nl_param_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1367
    },
    {
      "addr": 18446744071596331471,
      "name": "devlink_nl_param_fill.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/devlink/leftover.c:4032",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_param_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_param_get_dump_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595862944,
      "name": "devlink_nl_param_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
    },
    {
      "addr": 18446744071596893397,
      "name": "devlink_nl_param_fill.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/devlink/param.c:237",
      "file": "net/devlink/param.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/param.c:devlink_nl_param_get_doit",
        "net/devlink/param.c:devlink_nl_param_get_dump_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596727600,
      "name": "devlink_nl_param_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
    },
    {
      "addr": 18446744071597818381,
      "name": "devlink_nl_param_fill.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502405024,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502405024,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235141544,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235141544,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1364
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295951792,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295951792,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278613828,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278613828,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438128,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071588448269,
      "name": "devlink_nl_param_fill.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150816,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071588160957,
      "name": "devlink_nl_param_fill.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770304,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071588780445,
      "name": "devlink_nl_param_fill.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_param_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_param_fill",
      "external": false,
      "loc": "net/core/devlink.c:3033",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_dumpit",
        "net/core/devlink.c:devlink_param_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588910832,
      "name": "devlink_nl_param_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1627
    },
    {
      "addr": 18446744071588920973,
      "name": "devlink_nl_param_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int devlink_nl_param_fill(struct sk_buff * msg, struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
