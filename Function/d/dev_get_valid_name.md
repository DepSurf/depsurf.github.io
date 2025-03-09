# Function: <code>dev_get_valid_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586284848,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1114",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:register_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284848,
      "name": "dev_get_valid_name",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586712960,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1118",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712960,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898640,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1117",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898640,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587023904,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1149",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023904,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587521888,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1146",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521888,
      "name": "dev_get_valid_name",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587822624,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1146",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822624,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587955600,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1148",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955600,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588270304,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1144",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270304,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588476656,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476656,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589343088,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1255",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589343088,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350224,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1257",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350224,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240176,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1305",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240176,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964352,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1180",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964352,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591510480,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1127",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510480,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593281712,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1127",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593281712,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593740560,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1152",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593740560,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594576396,
      "name": "dev_get_valid_name",
      "external": false,
      "loc": "net/core/dev.c:1165",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502005184,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502005184,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234760364,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234760364,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295442272,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295442272,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278295544,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278295544,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588083440,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083440,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587797008,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587797008,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588415216,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415216,
      "name": "dev_get_valid_name",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_get_valid_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588553808,
      "name": "dev_get_valid_name",
      "external": true,
      "loc": "net/core/dev.c:1062",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553808,
      "name": "dev_get_valid_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int dev_get_valid_name(struct net * net, struct net_device * dev, const char * name)
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
