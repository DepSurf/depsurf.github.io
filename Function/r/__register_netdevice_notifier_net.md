# Function: <code>__register_netdevice_notifier_net</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327200,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1871",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327200,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589326512,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1896",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326512,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222224,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1965",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222224,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589944320,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1840",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944320,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591478768,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1789",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591478768,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593247680,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1774",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593247680,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593708496,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1800",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593708496,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```

```json
{
  "name": "__register_netdevice_notifier_net",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594487360,
      "name": "__register_netdevice_notifier_net",
      "external": false,
      "loc": "net/core/dev.c:1804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice_notifier_dev_net",
        "net/core/dev.c:register_netdevice_notifier_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594487360,
      "name": "__register_netdevice_notifier_net",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __register_netdevice_notifier_net(struct net * net, struct notifier_block * nb, bool ignore_call_fail)
```
</details>
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
