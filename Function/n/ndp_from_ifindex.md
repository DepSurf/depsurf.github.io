# Function: <code>ndp_from_ifindex</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111840,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589114964,
      "name": "ndp_from_ifindex.cold.9",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:38",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589342848,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589348628,
      "name": "ndp_from_ifindex.cold.12",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798336,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589803838,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021504,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071590027054,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591056838,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591119516,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591049848,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591891064,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593610341,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595539317,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596047893,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596912789,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503771928,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503771928,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236393400,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236393400,
      "name": "ndp_from_ifindex",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297612144,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297612144,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279683566,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279683566,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589625104,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589630654,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589349632,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589355182,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590067136,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071590072686,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```

```json
{
  "name": "ndp_from_ifindex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndp_from_ifindex",
      "external": false,
      "loc": "net/ncsi/ncsi-netlink.c:34",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117216,
      "name": "ndp_from_ifindex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071590122766,
      "name": "ndp_from_ifindex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct ncsi_dev_priv * ndp_from_ifindex(struct net * net, u32 ifindex)
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
