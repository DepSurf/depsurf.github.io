# Function: <code>devlink_nl_trap_fill</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588821376,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588821376,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589717616,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5972",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589717616,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589745872,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:6823",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589745872,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589637520,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:7026",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637520,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:7697",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590392848,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
    },
    {
      "addr": 18446744071592708789,
      "name": "devlink_nl_trap_fill.cold",
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:8190",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591971456,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071594595044,
      "name": "devlink_nl_trap_fill.cold",
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:8729",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593782240,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071596331758,
      "name": "devlink_nl_trap_fill.cold",
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/devlink/leftover.c:5585",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_trap_get_dump_one",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595881152,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071596893680,
      "name": "devlink_nl_trap_fill.cold",
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/devlink/trap.c:257",
      "file": "net/devlink/trap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devlink_nl_trap_get_dump_one",
        "net/devlink/trap.c:devlink_nl_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596760592,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
    },
    {
      "addr": 18446744071597819744,
      "name": "devlink_nl_trap_fill.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502394800,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502394800,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235130172,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235130172,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295937136,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295937136,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278607340,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278607340,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427760,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427760,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140448,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140448,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759936,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759936,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900464,
      "name": "devlink_nl_trap_fill",
      "external": false,
      "loc": "net/core/devlink.c:5380",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900464,
      "name": "devlink_nl_trap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int devlink_nl_trap_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_item * trap_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```
</details>
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
