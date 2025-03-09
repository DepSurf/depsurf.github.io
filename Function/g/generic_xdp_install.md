# Function: <code>generic_xdp_install</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_xdp * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587049984,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:4343",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587049984,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587550704,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:4569",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587550704,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855232,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:4698",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_xdp_uninstall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855232,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587995568,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5118",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995568,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588307296,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5157",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307296,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588513872,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588513872,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589384736,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5430",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384736,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589392560,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5484",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392560,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289440,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5608",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289440,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5597",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590017008,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071592700066,
      "name": "generic_xdp_install.cold",
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5634",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591556912,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071594586384,
      "name": "generic_xdp_install.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5625",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593329936,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071596325234,
      "name": "generic_xdp_install.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5601",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593791760,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071596855471,
      "name": "generic_xdp_install.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5683",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594572352,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071597780423,
      "name": "generic_xdp_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502047256,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502047256,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234799928,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234799928,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295496256,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295496256,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278333572,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278333572,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588120608,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588120608,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587833440,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833440,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588452432,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452432,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_bpf * xdp)
```

```json
{
  "name": "generic_xdp_install",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588589344,
      "name": "generic_xdp_install",
      "external": false,
      "loc": "net/core/dev.c:5059",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589344,
      "name": "generic_xdp_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int generic_xdp_install(struct net_device * dev, struct netdev_xdp * xdp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct netdev_xdp * xdp</code> ➡️ <code>struct netdev_bpf * xdp</code>
</li>
</ul>
</details>
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
