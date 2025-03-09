# Function: <code>devlink_port_function_set</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589750840,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/core/devlink.c:1023",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink * devlink, struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589619440,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/core/devlink.c:1109",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589619440,
      "name": "devlink_port_function_set",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590384736,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/core/devlink.c:1372",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590384736,
      "name": "devlink_port_function_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
int devlink_port_function_set(struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591954928,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/core/devlink.c:1600",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591954928,
      "name": "devlink_port_function_set",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593777152,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/core/devlink.c:1834",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593777152,
      "name": "devlink_port_function_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
int devlink_port_function_set(struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595873312,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/devlink/leftover.c:1229",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595873312,
      "name": "devlink_port_function_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1113
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
int devlink_port_function_set(struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_port_function_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596699280,
      "name": "devlink_port_function_set",
      "external": false,
      "loc": "net/devlink/port.c:732",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_nl_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596699280,
      "name": "devlink_port_function_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int devlink_port_function_set(struct devlink * devlink, struct devlink_port * port, const struct nlattr * attr, struct netlink_ext_ack * extack)
```
</details>
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
<code>devlink, port, attr, extack</code> ➡️ <code>port, attr, extack</code>
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
