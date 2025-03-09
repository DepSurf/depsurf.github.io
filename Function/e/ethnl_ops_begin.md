# Function: <code>ethnl_ops_begin</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589888681,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589890300,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/linkinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589892294,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589892896,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/linkstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkstate.c:linkstate_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589893697,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589894690,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/wol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589897962,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899124,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/rings.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589900498,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/channels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589903049,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/coalesce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589904739,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589906030,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/eee.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589907206,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/tsinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589910640,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:249",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589928025,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929446,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589931389,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589932067,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkstate.c:linkstate_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589932900,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589933812,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/wol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936914,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937967,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/rings.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589939206,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/channels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941591,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/coalesce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589943555,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589944740,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/eee.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589945878,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/tsinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589949288,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589835257,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837302,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589839748,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589840435,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/linkstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkstate.c:linkstate_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589841268,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842180,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/wol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589845268,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846335,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/rings.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847574,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/channels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589850038,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/coalesce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589852051,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589853236,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/eee.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589854358,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/tsinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tsinfo.c:tsinfo_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589857771,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861628,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589863282,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/eeprom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/eeprom.c:eeprom_prepare_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589864271,
      "name": "ethnl_ops_begin",
      "external": false,
      "loc": "net/ethtool/netlink.h:250",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_prepare_data"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ethnl_ops_begin(struct net_device * dev)
```

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590588384,
      "name": "ethnl_ops_begin",
      "external": true,
      "loc": "net/ethtool/netlink.c:33",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data",
        "net/ethtool/linkstate.c:linkstate_prepare_data",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/eeprom.c:eeprom_prepare_data",
        "net/ethtool/stats.c:stats_prepare_data",
        "net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590588384,
      "name": "ethnl_ops_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int ethnl_ops_begin(struct net_device * dev)
```

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592206752,
      "name": "ethnl_ops_begin",
      "external": true,
      "loc": "net/ethtool/netlink.c:33",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data",
        "net/ethtool/linkstate.c:linkstate_prepare_data",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/eeprom.c:eeprom_prepare_data",
        "net/ethtool/stats.c:stats_prepare_data",
        "net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data",
        "net/ethtool/module.c:ethnl_set_module",
        "net/ethtool/module.c:module_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592206752,
      "name": "ethnl_ops_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ethnl_ops_begin(struct net_device * dev)
```

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594036288,
      "name": "ethnl_ops_begin",
      "external": true,
      "loc": "net/ethtool/netlink.c:33",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data",
        "net/ethtool/rss.c:rss_prepare_data",
        "net/ethtool/linkstate.c:linkstate_prepare_data",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:debug_prepare_data",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/wol.c:wol_prepare_data",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/rings.c:rings_prepare_data",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/channels.c:channels_prepare_data",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/coalesce.c:coalesce_prepare_data",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/pause.c:pause_prepare_data",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/eee.c:eee_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/eeprom.c:eeprom_prepare_data",
        "net/ethtool/stats.c:stats_prepare_data",
        "net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data",
        "net/ethtool/module.c:ethnl_set_module",
        "net/ethtool/module.c:module_prepare_data",
        "net/ethtool/pse-pd.c:ethnl_set_pse",
        "net/ethtool/pse-pd.c:pse_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594036288,
      "name": "ethnl_ops_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ethnl_ops_begin(struct net_device * dev)
```

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594414080,
      "name": "ethnl_ops_begin",
      "external": true,
      "loc": "net/ethtool/netlink.c:33",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data",
        "net/ethtool/rss.c:rss_prepare_data",
        "net/ethtool/linkstate.c:linkstate_prepare_data",
        "net/ethtool/debug.c:debug_prepare_data",
        "net/ethtool/wol.c:wol_prepare_data",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/rings.c:rings_prepare_data",
        "net/ethtool/channels.c:channels_prepare_data",
        "net/ethtool/coalesce.c:coalesce_prepare_data",
        "net/ethtool/pause.c:pause_prepare_data",
        "net/ethtool/eee.c:eee_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/eeprom.c:eeprom_prepare_data",
        "net/ethtool/stats.c:stats_prepare_data",
        "net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data",
        "net/ethtool/mm.c:ethtool_dev_mm_supported",
        "net/ethtool/mm.c:mm_prepare_data",
        "net/ethtool/module.c:module_prepare_data",
        "net/ethtool/pse-pd.c:pse_prepare_data",
        "net/ethtool/plca.c:plca_get_status_prepare_data",
        "net/ethtool/plca.c:plca_get_cfg_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594414080,
      "name": "ethnl_ops_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ethnl_ops_begin(struct net_device * dev)
```

```json
{
  "name": "ethnl_ops_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595216560,
      "name": "ethnl_ops_begin",
      "external": true,
      "loc": "net/ethtool/netlink.c:33",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_set_doit",
        "net/ethtool/strset.c:strset_prepare_data",
        "net/ethtool/linkinfo.c:linkinfo_prepare_data",
        "net/ethtool/linkmodes.c:linkmodes_prepare_data",
        "net/ethtool/rss.c:rss_prepare_data",
        "net/ethtool/linkstate.c:linkstate_prepare_data",
        "net/ethtool/debug.c:debug_prepare_data",
        "net/ethtool/wol.c:wol_prepare_data",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:privflags_prepare_data",
        "net/ethtool/rings.c:rings_prepare_data",
        "net/ethtool/channels.c:channels_prepare_data",
        "net/ethtool/coalesce.c:coalesce_prepare_data",
        "net/ethtool/pause.c:pause_prepare_data",
        "net/ethtool/eee.c:eee_prepare_data",
        "net/ethtool/tsinfo.c:tsinfo_prepare_data",
        "net/ethtool/cabletest.c:ethnl_act_cable_test_tdr",
        "net/ethtool/cabletest.c:ethnl_act_cable_test",
        "net/ethtool/fec.c:fec_prepare_data",
        "net/ethtool/eeprom.c:eeprom_prepare_data",
        "net/ethtool/stats.c:stats_prepare_data",
        "net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data",
        "net/ethtool/mm.c:ethtool_dev_mm_supported",
        "net/ethtool/mm.c:mm_prepare_data",
        "net/ethtool/module.c:module_prepare_data",
        "net/ethtool/pse-pd.c:pse_prepare_data",
        "net/ethtool/plca.c:plca_get_status_prepare_data",
        "net/ethtool/plca.c:plca_get_cfg_prepare_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595216560,
      "name": "ethnl_ops_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int ethnl_ops_begin(struct net_device * dev)
```
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
