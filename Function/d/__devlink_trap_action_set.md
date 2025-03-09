# Function: <code>__devlink_trap_action_set</code>

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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588796036,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589670874,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:6096",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589684672,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:6947",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589684672,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589567872,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:7150",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589567872,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590312624,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:7829",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590312624,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591898896,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:8322",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591898896,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593703712,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:8851",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593703712,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595817168,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/devlink/leftover.c:5703",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595817168,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596754800,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/devlink/trap.c:374",
      "file": "net/devlink/trap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/trap.c:devlink_nl_trap_group_set_doit",
        "net/devlink/trap.c:devlink_nl_trap_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596754800,
      "name": "__devlink_trap_action_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502366708,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235095620,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295897684,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278582968,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588402420,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588115108,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588734596,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
  "name": "__devlink_trap_action_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588875060,
      "name": "__devlink_trap_action_set",
      "external": false,
      "loc": "net/core/devlink.c:5504",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_set_doit"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __devlink_trap_action_set(struct devlink * devlink, struct devlink_trap_item * trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack * extack)
```
</details>
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
