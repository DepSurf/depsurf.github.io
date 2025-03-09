# Function: <code>igmpv3_del_delrec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586802999,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1124",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_inc_group"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587257281,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1123",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_inc_group"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587456816,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1141",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456816,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587594048,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1150",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594048,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588117104,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1178",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588117104,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588471824,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1178",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:__ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471824,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588665680,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1189",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:__ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665680,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080240,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080240,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589304400,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589304400,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590275808,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1204",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590275808,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328608,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1204",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328608,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590244224,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1211",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244224,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591027808,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1211",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591027808,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592675200,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1214",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592675200,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594543344,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1214",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594543344,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594935136,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1215",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594935136,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595747360,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1217",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595747360,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502931752,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502931752,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235616720,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235616720,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296594736,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296594736,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279015104,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279015104,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588910576,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588910576,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622512,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622512,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589346960,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346960,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```

```json
{
  "name": "igmpv3_del_delrec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389312,
      "name": "igmpv3_del_delrec",
      "external": false,
      "loc": "net/ipv4/igmp.c:1206",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_up",
        "net/ipv4/igmp.c:ip_mc_remap",
        "net/ipv4/igmp.c:____ip_mc_inc_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389312,
      "name": "igmpv3_del_delrec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void igmpv3_del_delrec(struct in_device * in_dev, struct ip_mc_list * im)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
