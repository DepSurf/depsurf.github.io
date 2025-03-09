# Function: <code>devlink_reload</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devlink_reload(struct devlink * devlink, struct net * dest_net, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589714288,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:2795",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714288,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589753280,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:3179",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753280,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589634992,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:3382",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634992,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:3947",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388960,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071592708705,
      "name": "devlink_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:4462",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591977088,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
    },
    {
      "addr": 18446744071594595086,
      "name": "devlink_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_reload",
      "external": false,
      "loc": "net/core/devlink.c:4728",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_pernet_pre_exit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593787840,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    },
    {
      "addr": 18446744071596331800,
      "name": "devlink_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_reload",
      "external": true,
      "loc": "net/devlink/dev.c:350",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596893813,
      "name": "devlink_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071595902592,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 * actions_performed, struct netlink_ext_ack * extack)
```

```json
{
  "name": "devlink_reload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_reload",
      "external": true,
      "loc": "net/devlink/dev.c:442",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/core.c:devlink_pernet_pre_exit",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_reload_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597817806,
      "name": "devlink_reload.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071596686992,
      "name": "devlink_reload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
int devlink_reload(struct devlink * devlink, struct net * dest_net, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum devlink_reload_action action</code>
</li>
<li>
<b>Param added. </b>
<code>enum devlink_reload_limit limit</code>
</li>
<li>
<b>Param added. </b>
<code>u32 * actions_performed</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink, dest_net, extack</code> ➡️ <code>devlink, dest_net, action, limit, actions_performed, extack</code>
</li>
</ul>
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
