# Function: <code>devlink_resource_put</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2519",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587840,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
    },
    {
      "addr": 18446744071588618680,
      "name": "devlink_resource_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588803424,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588803424,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589689232,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2553",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689232,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589721312,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2885",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721312,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589596976,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:3088",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596976,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:3650",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348800,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071592707925,
      "name": "devlink_resource_put.isra.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:4165",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591938528,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071594594514,
      "name": "devlink_resource_put.isra.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:4430",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593742432,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071596331174,
      "name": "devlink_resource_put.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/devlink/leftover.c:3648",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595851632,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071596893329,
      "name": "devlink_resource_put.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/devlink/resource.c:165",
      "file": "net/devlink/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596721104,
      "name": "devlink_resource_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071597818283,
      "name": "devlink_resource_put.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502377824,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502377824,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235110632,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235110632,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295914256,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295914256,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278594960,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278594960,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409808,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409808,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588122496,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122496,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741984,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741984,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```

```json
{
  "name": "devlink_resource_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588882512,
      "name": "devlink_resource_put",
      "external": false,
      "loc": "net/core/devlink.c:2521",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_resource_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588882512,
      "name": "devlink_resource_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int devlink_resource_put(struct devlink * devlink, struct sk_buff * skb, struct devlink_resource * resource)
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
