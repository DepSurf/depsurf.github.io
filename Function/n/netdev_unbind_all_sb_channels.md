# Function: <code>netdev_unbind_all_sb_channels</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587967936,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2524",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967936,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588266640,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2534",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266640,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472944,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472944,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589344213,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2812",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589344933,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2837",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589235016,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2905",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589960072,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2780",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591496808,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2757",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593265800,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2742",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593723400,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2770",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594504104,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2773",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501992960,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501992960,
      "name": "netdev_unbind_all_sb_channels",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234764328,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234764328,
      "name": "netdev_unbind_all_sb_channels",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295434080,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295434080,
      "name": "netdev_unbind_all_sb_channels",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278302784,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278302784,
      "name": "netdev_unbind_all_sb_channels",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079728,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079728,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793296,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793296,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411504,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411504,
      "name": "netdev_unbind_all_sb_channels",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```

```json
{
  "name": "netdev_unbind_all_sb_channels",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588550096,
      "name": "netdev_unbind_all_sb_channels",
      "external": false,
      "loc": "net/core/dev.c:2452",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_set_num_tc",
        "net/core/dev.c:netdev_reset_tc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550096,
      "name": "netdev_unbind_all_sb_channels",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void netdev_unbind_all_sb_channels(struct net_device * dev)
```
</details>
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
void netdev_unbind_all_sb_channels(struct net_device * dev)
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
