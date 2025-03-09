# Function: <code>__switchdev_handle_port_attr_set</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589771488,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771488,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589995200,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589995200,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591025824,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:560",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591025824,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591089600,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:561",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591089600,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591020448,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:492",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591020448,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591859408,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:754",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591859408,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593575776,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:759",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593575776,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595501168,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:759",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595501168,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596009872,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:759",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596009872,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596873328,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:832",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596873328,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503736640,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503736640,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236366564,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236366564,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297576768,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297576768,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279657692,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279657692,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598800,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598800,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323328,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323328,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590040832,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590040832,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
```

```json
{
  "name": "__switchdev_handle_port_attr_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090864,
      "name": "__switchdev_handle_port_attr_set",
      "external": false,
      "loc": "net/switchdev/switchdev.c:554",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_attr_set",
        "net/switchdev/switchdev.c:__switchdev_handle_port_attr_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090864,
      "name": "__switchdev_handle_port_attr_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __switchdev_handle_port_attr_set(struct net_device * dev, struct switchdev_notifier_port_attr_info * port_attr_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *) set_cb</code> ➡️ <code>int (*)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb</code> ➡️ <code>int (*)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *) set_cb</code>
</li>
</ul>
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
