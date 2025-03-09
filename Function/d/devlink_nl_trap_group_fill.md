# Function: <code>devlink_nl_trap_group_fill</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588820112,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588820112,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589704000,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:6203",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589704000,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589734080,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:7049",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589734080,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589613136,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:7252",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589613136,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:7931",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590370720,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071592708128,
      "name": "devlink_nl_trap_group_fill.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:8424",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591957168,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071594594715,
      "name": "devlink_nl_trap_group_fill.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:8953",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593759984,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071596331388,
      "name": "devlink_nl_trap_group_fill.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/devlink/leftover.c:5805",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_dump_one",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595867552,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071596893555,
      "name": "devlink_nl_trap_group_fill.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/devlink/trap.c:475",
      "file": "net/devlink/trap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devlink_nl_trap_group_get_dump_one",
        "net/devlink/trap.c:devlink_nl_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596757744,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071597819702,
      "name": "devlink_nl_trap_group_fill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502393544,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502393544,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235128956,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235128956,
      "name": "devlink_nl_trap_group_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295935296,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295935296,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278606292,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278606292,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588426496,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426496,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588139184,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139184,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758672,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758672,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
  "name": "devlink_nl_trap_group_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588899200,
      "name": "devlink_nl_trap_group_fill",
      "external": false,
      "loc": "net/core/devlink.c:5598",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899200,
      "name": "devlink_nl_trap_group_fill.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
int devlink_nl_trap_group_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_group_item * group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```
</details>
</li>
</ul>
