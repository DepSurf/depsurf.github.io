# Function: <code>netdev_name_in_use</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool netdev_name_in_use(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_in_use",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591525122,
      "name": "netdev_name_in_use",
      "external": true,
      "loc": "net/core/dev.c:321",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509648,
      "name": "netdev_name_in_use",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool netdev_name_in_use(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_in_use",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593298722,
      "name": "netdev_name_in_use",
      "external": true,
      "loc": "net/core/dev.c:321",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593280800,
      "name": "netdev_name_in_use",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool netdev_name_in_use(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_in_use",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593758420,
      "name": "netdev_name_in_use",
      "external": true,
      "loc": "net/core/dev.c:319",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593739648,
      "name": "netdev_name_in_use",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool netdev_name_in_use(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_in_use",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594537252,
      "name": "netdev_name_in_use",
      "external": true,
      "loc": "net/core/dev.c:320",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594516320,
      "name": "netdev_name_in_use",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool netdev_name_in_use(struct net * net, const char * name)
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
