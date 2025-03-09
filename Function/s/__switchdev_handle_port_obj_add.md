# Function: <code>__switchdev_handle_port_obj_add</code>

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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589314384,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:614",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589314384,
      "name": "__switchdev_handle_port_obj_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770992,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770992,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589994704,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589994704,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591025312,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591025312,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591089072,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:447",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591089072,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019936,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:381",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019936,
      "name": "__switchdev_handle_port_obj_add",
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591858896,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:641",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591858896,
      "name": "__switchdev_handle_port_obj_add",
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593579072,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:535",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign",
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593579072,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595504784,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:535",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign",
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595504784,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596013488,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:535",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign",
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596013488,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596877568,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:608",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign",
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596877568,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503735960,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503735960,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236366024,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236366024,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297575984,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297575984,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279657218,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279657218,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598304,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598304,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322832,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322832,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590040336,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590040336,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
```

```json
{
  "name": "__switchdev_handle_port_obj_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090368,
      "name": "__switchdev_handle_port_obj_add",
      "external": false,
      "loc": "net/switchdev/switchdev.c:448",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_port_obj_add",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090368,
      "name": "__switchdev_handle_port_obj_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __switchdev_handle_port_obj_add(struct net_device * dev, struct switchdev_notifier_port_obj_info * port_obj_info, bool (*)(const struct net_device *) check_cb, int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb)
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
<b>Param type changed. </b>
<code>int (*)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *) add_cb</code> ➡️ <code>int (*)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb</code>
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
<code>int (*)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb</code> ➡️ <code>int (*)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *) add_cb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, port_obj_info, check_cb, add_cb</code> ➡️ <code>dev, port_obj_info, check_cb, foreign_dev_check_cb, add_cb</code>
</li>
</ul>
</details>
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
