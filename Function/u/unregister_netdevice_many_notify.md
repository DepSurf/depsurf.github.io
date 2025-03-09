# Function: <code>unregister_netdevice_many_notify</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void unregister_netdevice_many_notify(struct list_head * head, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "unregister_netdevice_many_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_many_notify",
      "external": true,
      "loc": "net/core/dev.c:10775",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:rtnl_dellink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325297,
      "name": "unregister_netdevice_many_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071593331408,
      "name": "unregister_netdevice_many_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1746
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
void unregister_netdevice_many_notify(struct list_head * head, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "unregister_netdevice_many_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_many_notify",
      "external": true,
      "loc": "net/core/dev.c:10791",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:rtnl_dellink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596855534,
      "name": "unregister_netdevice_many_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071593793232,
      "name": "unregister_netdevice_many_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
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
void unregister_netdevice_many_notify(struct list_head * head, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "unregister_netdevice_many_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_many_notify",
      "external": true,
      "loc": "net/core/dev.c:11002",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:rtnl_dellink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597780486,
      "name": "unregister_netdevice_many_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071594573952,
      "name": "unregister_netdevice_many_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1875
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void unregister_netdevice_many_notify(struct list_head * head, u32 portid, const struct nlmsghdr * nlh)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
