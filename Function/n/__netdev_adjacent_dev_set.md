# Function: <code>__netdev_adjacent_dev_set</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455008,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455008,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322992,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7800",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322992,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589321856,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7997",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589321856,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589217600,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:8256",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217600,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589941280,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:8246",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941280,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591474624,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7777",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591474624,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593244128,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7763",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593244128,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593704816,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7768",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593704816,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594483152,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7886",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_commit",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594483152,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501980000,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501980000,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234734092,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234734092,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295408112,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295408112,
      "name": "__netdev_adjacent_dev_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278278378,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278278378,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061792,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061792,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587774880,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587774880,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393568,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393568,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```

```json
{
  "name": "__netdev_adjacent_dev_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588529248,
      "name": "__netdev_adjacent_dev_set",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_adjacent_change_abort",
        "net/core/dev.c:netdev_adjacent_change_prepare",
        "net/core/dev.c:netdev_adjacent_change_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529248,
      "name": "__netdev_adjacent_dev_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __netdev_adjacent_dev_set(struct net_device * upper_dev, struct net_device * lower_dev, bool val)
```
</details>
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
