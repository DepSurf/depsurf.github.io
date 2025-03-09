# Function: <code>devlink_nl_trap_policer_fill</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589721616,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:6490",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721616,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589756416,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:7355",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589756416,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589604944,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:7558",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589604944,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590351552,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:8245",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590351552,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591936448,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:8738",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591936448,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593790096,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/core/devlink.c:9257",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593790096,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595849216,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/devlink/leftover.c:6099",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_dump_one",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595849216,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
```

```json
{
  "name": "devlink_nl_trap_policer_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596755504,
      "name": "devlink_nl_trap_policer_fill",
      "external": false,
      "loc": "net/devlink/trap.c:767",
      "file": "net/devlink/trap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devlink_nl_trap_policer_get_dump_one",
        "net/devlink/trap.c:devlink_nl_trap_policer_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596755504,
      "name": "devlink_nl_trap_policer_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int devlink_nl_trap_policer_fill(struct sk_buff * msg, struct devlink * devlink, const struct devlink_trap_policer_item * policer_item, enum devlink_command cmd, u32 portid, u32 seq, int flags)
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
