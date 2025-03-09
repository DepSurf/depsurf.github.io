# Function: <code>addrconf_dev_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587042832,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3065",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587491413,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3167",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587695207,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3183",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587831440,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3238",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587831440,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588360272,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3224",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360272,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588717760,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3275",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717760,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588938656,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3291",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938656,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381760,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3329",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381760,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589606192,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589606192,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590615600,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3296",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590615600,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590676272,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3323",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590676272,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590602032,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3325",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590602032,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3351",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591414976,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071592737163,
      "name": "addrconf_dev_config.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3358",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593092656,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071594623742,
      "name": "addrconf_dev_config.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594987532,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3358",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_init_auto_addrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595380898,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3363",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_init_auto_addrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596222050,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3414",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_init_auto_addrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503282256,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503282256,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235954024,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235954024,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297034752,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297034752,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279305806,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279305806,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210560,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210560,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588935552,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588935552,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647424,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647424,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void addrconf_dev_config(struct net_device * dev)
```

```json
{
  "name": "addrconf_dev_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589696416,
      "name": "addrconf_dev_config",
      "external": false,
      "loc": "net/ipv6/addrconf.c:3331",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589696416,
      "name": "addrconf_dev_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void addrconf_dev_config(struct net_device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void addrconf_dev_config(struct net_device * dev)
```
</details>
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
