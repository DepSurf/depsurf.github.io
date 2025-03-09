# Function: <code>netdev_name_node_lookup</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:275",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589338704,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589391916,
      "name": "netdev_name_node_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:278",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589340304,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071591629088,
      "name": "netdev_name_node_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:280",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236736,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071591572521,
      "name": "netdev_name_node_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:282",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589961264,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071592697766,
      "name": "netdev_name_node_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:297",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509520,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071594584173,
      "name": "netdev_name_node_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593280640,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:297",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593280640,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593758420,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:295",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593739488,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
```

```json
{
  "name": "netdev_name_node_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594537330,
      "name": "netdev_name_node_lookup",
      "external": false,
      "loc": "net/core/dev.c:296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594516160,
      "name": "netdev_name_node_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct netdev_name_node * netdev_name_node_lookup(struct net * net, const char * name)
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
