# Function: <code>ethtool_notify</code>

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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589877840,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:646",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_ringparam",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589877840,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589917120,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:648",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_ringparam",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589917120,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824704,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:654",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/fec.c:ethnl_set_fec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824704,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:692",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/fec.c:ethnl_set_fec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592711771,
      "name": "ethtool_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071590586928,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:696",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/module.c:ethnl_set_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594597829,
      "name": "ethtool_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071592206304,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:701",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/linkinfo.c:ethnl_set_linkinfo",
        "net/ethtool/linkmodes.c:ethnl_set_linkmodes",
        "net/ethtool/debug.c:ethnl_set_debug",
        "net/ethtool/wol.c:ethnl_set_wol",
        "net/ethtool/privflags.c:ethnl_set_privflags",
        "net/ethtool/rings.c:ethnl_set_rings",
        "net/ethtool/channels.c:ethnl_set_channels",
        "net/ethtool/coalesce.c:ethnl_set_coalesce",
        "net/ethtool/pause.c:ethnl_set_pause",
        "net/ethtool/eee.c:ethnl_set_eee",
        "net/ethtool/fec.c:ethnl_set_fec",
        "net/ethtool/module.c:ethnl_set_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596333792,
      "name": "ethtool_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071594035792,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:771",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/netlink.c:ethnl_default_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596862758,
      "name": "ethtool_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071594413584,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
```

```json
{
  "name": "ethtool_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_notify",
      "external": true,
      "loc": "net/ethtool/netlink.c:742",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_channels",
        "net/ethtool/ioctl.c:ethtool_set_coalesce",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_settings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/ioctl.c:ethtool_set_link_ksettings",
        "net/ethtool/netlink.c:ethnl_default_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597787828,
      "name": "ethtool_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071595216048,
      "name": "ethtool_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void ethtool_notify(struct net_device * dev, unsigned int cmd, const void * data)
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
