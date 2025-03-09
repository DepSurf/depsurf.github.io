# Function: <code>__netdev_adjacent_dev_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275280,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:5248",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_adjacent_dev_unlink",
        "net/core/dev.c:__netdev_adjacent_dev_unlink",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275280,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701024,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:5638",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink",
        "net/core/dev.c:__netdev_adjacent_dev_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701024,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893296,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:5888",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893296,
      "name": "__netdev_adjacent_dev_remove.constprop.109",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587019200,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:6096",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019200,
      "name": "__netdev_adjacent_dev_remove.constprop.115",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587516944,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:6237",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516944,
      "name": "__netdev_adjacent_dev_remove.constprop.118",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587817424,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:6367",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587817424,
      "name": "__netdev_adjacent_dev_remove.constprop.134",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587952752,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:6942",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587952752,
      "name": "__netdev_adjacent_dev_remove.constprop.143",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588263616,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:6952",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263616,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588468752,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468752,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589345024,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7554",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589345024,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589346464,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7728",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346464,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245168,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7987",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245168,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7977",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970096,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071592698044,
      "name": "__netdev_adjacent_dev_remove.cold",
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7508",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591517376,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071594584383,
      "name": "__netdev_adjacent_dev_remove.cold",
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7494",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593291792,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071596324095,
      "name": "__netdev_adjacent_dev_remove.cold",
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7499",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593747264,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071596854123,
      "name": "__netdev_adjacent_dev_remove.cold",
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
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
```

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594526208,
      "name": "__netdev_adjacent_dev_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071597779113,
      "name": "__netdev_adjacent_dev_remove.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502008400,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502008400,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234754036,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234754036,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295438352,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295438352,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278291716,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278291716,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588075536,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075536,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587789104,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789104,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588407312,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407312,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_adjacent_dev_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588545904,
      "name": "__netdev_adjacent_dev_remove",
      "external": false,
      "loc": "net/core/dev.c:7163",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588545904,
      "name": "__netdev_adjacent_dev_remove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, struct list_head * dev_list)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device * dev, struct net_device * adj_dev, u16 ref_nr, struct list_head * dev_list)
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
