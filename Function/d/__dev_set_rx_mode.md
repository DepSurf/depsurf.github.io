# Function: <code>__dev_set_rx_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586306384,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:5835",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_uc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306384,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586734624,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:6286",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734624,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920416,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:6430",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920416,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045728,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:6595",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045728,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587546096,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:6752",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546096,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587849792,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:6888",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587849792,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989680,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7463",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989680,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588301408,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7473",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301408,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588507856,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588507856,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379024,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8175",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:dev_mc_add_global",
        "net/core/dev_addr_lists.c:dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379024,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589384800,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8420",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384800,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589281536,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8679",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589281536,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8669",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592699468,
      "name": "__dev_set_rx_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071590008768,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8434",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594585635,
      "name": "__dev_set_rx_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071591547424,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8420",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324619,
      "name": "__dev_set_rx_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071593321568,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8426",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854919,
      "name": "__dev_set_rx_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071593783392,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:8544",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_change_flags",
        "net/core/dev.c:__dev_set_allmulti",
        "net/core/dev.c:dev_set_promiscuity",
        "net/core/dev.c:__dev_open",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:dev_mc_del_global",
        "net/core/dev_addr_lists.c:dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779927,
      "name": "__dev_set_rx_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071594564016,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502041080,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502041080,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234793056,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234793056,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295488096,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295488096,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278328154,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278328154,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588114592,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114592,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827424,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827424,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446416,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588446416,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __dev_set_rx_mode(struct net_device * dev)
```

```json
{
  "name": "__dev_set_rx_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588583328,
      "name": "__dev_set_rx_mode",
      "external": true,
      "loc": "net/core/dev.c:7762",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588583328,
      "name": "__dev_set_rx_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
