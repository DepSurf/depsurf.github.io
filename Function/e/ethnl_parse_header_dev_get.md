# Function: <code>ethnl_parse_header_dev_get</code>

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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589879184,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:36",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589879184,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589918496,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:48",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589918496,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589826064,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:48",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/fec.c:ethnl_set_fec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589826064,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590588640,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:88",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/fec.c:ethnl_set_fec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590588640,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592207024,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:88",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/module.c:ethnl_set_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207024,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594036592,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:88",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/module.c:ethnl_set_module",
        "net/ethtool/pse-pd.c:ethnl_set_pse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594036592,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594414384,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:88",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594414384,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
```

```json
{
  "name": "ethnl_parse_header_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595216880,
      "name": "ethnl_parse_header_dev_get",
      "external": true,
      "loc": "net/ethtool/netlink.c:88",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/netlink.c:ethnl_default_parse",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_start",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595216880,
      "name": "ethnl_parse_header_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int ethnl_parse_header_dev_get(struct ethnl_req_info * req_info, const struct nlattr * header, struct net * net, struct netlink_ext_ack * extack, bool require_dev)
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
