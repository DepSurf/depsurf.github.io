# Function: <code>__dev_change_net_namespace</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254064,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:11134",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254064,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1732
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
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:11141",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698537,
      "name": "__dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589979600,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1744
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
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:10924",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584734,
      "name": "__dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591522944,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1989
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
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:10928",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324290,
      "name": "__dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593296512,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2005
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
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:10945",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854329,
      "name": "__dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593756224,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1993
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
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```

```json
{
  "name": "__dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:11156",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779319,
      "name": "__dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594534624,
      "name": "__dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2383
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat, int new_ifindex)
```
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
