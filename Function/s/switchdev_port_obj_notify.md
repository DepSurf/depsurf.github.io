# Function: <code>switchdev_port_obj_notify</code>

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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589315824,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:356",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315824,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770432,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071589772765,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994160,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994160,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591024768,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591024768,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591088528,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591088528,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019552,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:193",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019552,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:193",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591859952,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071592747667,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:194",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593576384,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071594634230,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:194",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595501840,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071596365766,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:194",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596010544,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071596895567,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:223",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596874352,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071597820828,
      "name": "switchdev_port_obj_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503735208,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503735208,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236365276,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236365276,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297575056,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297575056,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279656666,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279656666,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589597760,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589597760,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322288,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322288,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590039792,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039792,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
```

```json
{
  "name": "switchdev_port_obj_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590089824,
      "name": "switchdev_port_obj_notify",
      "external": false,
      "loc": "net/switchdev/switchdev.c:221",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_obj_del_deferred",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now",
        "net/switchdev/switchdev.c:switchdev_port_obj_add_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089824,
      "name": "switchdev_port_obj_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device * dev, const struct switchdev_obj * obj, struct switchdev_trans * trans, struct netlink_ext_ack * extack)
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
<b>Param removed. </b>
<code>struct switchdev_trans * trans</code>
</li>
<li>
<b>Param reordered. </b>
<code>nt, dev, obj, trans, extack</code> ➡️ <code>nt, dev, obj, extack</code>
</li>
</ul>
</details>
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
