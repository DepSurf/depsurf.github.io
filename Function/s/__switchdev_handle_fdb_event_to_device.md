# Function: <code>__switchdev_handle_fdb_event_to_device</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __switchdev_handle_fdb_event_to_device(struct net_device * dev, struct net_device * orig_dev, long unsigned int event, const struct switchdev_notifier_fdb_info * fdb_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *) mod_cb)
```

```json
{
  "name": "__switchdev_handle_fdb_event_to_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593578464,
      "name": "__switchdev_handle_fdb_event_to_device",
      "external": false,
      "loc": "net/switchdev/switchdev.c:453",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593578464,
      "name": "__switchdev_handle_fdb_event_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int __switchdev_handle_fdb_event_to_device(struct net_device * dev, struct net_device * orig_dev, long unsigned int event, const struct switchdev_notifier_fdb_info * fdb_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *) mod_cb)
```

```json
{
  "name": "__switchdev_handle_fdb_event_to_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595504144,
      "name": "__switchdev_handle_fdb_event_to_device",
      "external": false,
      "loc": "net/switchdev/switchdev.c:453",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595504144,
      "name": "__switchdev_handle_fdb_event_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int __switchdev_handle_fdb_event_to_device(struct net_device * dev, struct net_device * orig_dev, long unsigned int event, const struct switchdev_notifier_fdb_info * fdb_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *) mod_cb)
```

```json
{
  "name": "__switchdev_handle_fdb_event_to_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596012848,
      "name": "__switchdev_handle_fdb_event_to_device",
      "external": false,
      "loc": "net/switchdev/switchdev.c:453",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596012848,
      "name": "__switchdev_handle_fdb_event_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int __switchdev_handle_fdb_event_to_device(struct net_device * dev, struct net_device * orig_dev, long unsigned int event, const struct switchdev_notifier_fdb_info * fdb_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *) mod_cb)
```

```json
{
  "name": "__switchdev_handle_fdb_event_to_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596876928,
      "name": "__switchdev_handle_fdb_event_to_device",
      "external": false,
      "loc": "net/switchdev/switchdev.c:526",
      "file": "net/switchdev/switchdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596876928,
      "name": "__switchdev_handle_fdb_event_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __switchdev_handle_fdb_event_to_device(struct net_device * dev, struct net_device * orig_dev, long unsigned int event, const struct switchdev_notifier_fdb_info * fdb_info, bool (*)(const struct net_device *) check_cb, bool (*)(const struct net_device *, const struct net_device *) foreign_dev_check_cb, int (*)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *) mod_cb)
```
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
