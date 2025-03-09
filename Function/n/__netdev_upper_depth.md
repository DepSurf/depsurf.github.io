# Function: <code>__netdev_upper_depth</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588469633,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589346822,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7322",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589348427,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7484",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589247155,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7743",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u8 __netdev_upper_depth(struct net_device * dev)
```

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956432,
      "name": "__netdev_upper_depth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071592697545,
      "name": "__netdev_upper_depth.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u8 __netdev_upper_depth(struct net_device * dev)
```

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7254",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591494016,
      "name": "__netdev_upper_depth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071594583731,
      "name": "__netdev_upper_depth.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u8 __netdev_upper_depth(struct net_device * dev)
```

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7240",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593262544,
      "name": "__netdev_upper_depth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071596323597,
      "name": "__netdev_upper_depth.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u8 __netdev_upper_depth(struct net_device * dev)
```

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7245",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593719952,
      "name": "__netdev_upper_depth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071596853465,
      "name": "__netdev_upper_depth.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u8 __netdev_upper_depth(struct net_device * dev)
```

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:7363",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594501232,
      "name": "__netdev_upper_depth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071597778549,
      "name": "__netdev_upper_depth.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502009080,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234755008,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295439232,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278292500,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588076417,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587789985,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588408193,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netdev_upper_depth",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588546785,
      "name": "__netdev_upper_depth",
      "external": false,
      "loc": "net/core/dev.c:6931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
u8 __netdev_upper_depth(struct net_device * dev)
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
