# Function: <code>__netdev_walk_all_upper_dev</code>

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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453632,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453632,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322048,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6993",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322048,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589320848,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:7150",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589320848,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216384,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:7409",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216384,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:7399",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955072,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071592697470,
      "name": "__netdev_walk_all_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6920",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591493328,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071594583675,
      "name": "__netdev_walk_all_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6906",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593261568,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071596323501,
      "name": "__netdev_walk_all_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6911",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593719232,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071596853409,
      "name": "__netdev_walk_all_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, struct netdev_nested_priv *) fn, struct netdev_nested_priv * priv)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:7029",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594500512,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071597778493,
      "name": "__netdev_walk_all_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501978248,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501978248,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234732608,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234732608,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295406128,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295406128,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278277150,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278277150,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588060416,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060416,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587773504,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773504,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392192,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392192,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```

```json
{
  "name": "__netdev_walk_all_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588527872,
      "name": "__netdev_walk_all_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:6602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_has_upper_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588527872,
      "name": "__netdev_walk_all_upper_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int __netdev_walk_all_upper_dev(struct net_device * dev, int (*)(struct net_device *, void *) fn, void * data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netdev_nested_priv * priv</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(struct net_device *, void *) fn</code> ➡️ <code>int (*)(struct net_device *, struct netdev_nested_priv *) fn</code>
</li>
</ul>
</details>
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
