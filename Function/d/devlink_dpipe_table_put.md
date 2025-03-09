# Function: <code>devlink_dpipe_table_put</code>

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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1780",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614944,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    },
    {
      "addr": 18446744071588619807,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588838768,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588838768,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589723696,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1814",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589723696,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758496,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:2146",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758496,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589640400,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:2349",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589640400,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:2911",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590391488,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
    },
    {
      "addr": 18446744071592708747,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:3426",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591970064,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071594595002,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:3690",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593780800,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071596331716,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/devlink/leftover.c:2908",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595879616,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071596893638,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/devlink/dpipe.c:156",
      "file": "net/devlink/dpipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596718304,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071597818178,
      "name": "devlink_dpipe_table_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502411080,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502411080,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235147464,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235147464,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295960544,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295960544,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278618742,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278618742,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445152,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588445152,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157840,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157840,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777328,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777328,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```

```json
{
  "name": "devlink_dpipe_table_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917856,
      "name": "devlink_dpipe_table_put",
      "external": false,
      "loc": "net/core/devlink.c:1782",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917856,
      "name": "devlink_dpipe_table_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int devlink_dpipe_table_put(struct sk_buff * skb, struct devlink_dpipe_table * table)
```
</details>
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
