# Function: <code>addrconf_sysctl_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587028717,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5813",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
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
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587476736,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6104",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
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
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587679966,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6183",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824784,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6463",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824784,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588355040,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6478",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355040,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588712448,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6598",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712448,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588931808,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6805",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931808,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589374480,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6899",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374480,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598912,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598912,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590609616,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6955",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590609616,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590670336,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6986",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670336,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590596016,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7020",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590596016,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591408800,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7093",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591408800,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593085968,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7130",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593085968,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594980304,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7143",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594980304,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595373456,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7149",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595373456,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596214608,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:7219",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596214608,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503275808,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503275808,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235947964,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235947964,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297025984,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297025984,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279299136,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279299136,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203280,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203280,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588928272,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928272,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589640144,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589640144,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
```

```json
{
  "name": "addrconf_sysctl_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689152,
      "name": "addrconf_sysctl_unregister",
      "external": false,
      "loc": "net/ipv6/addrconf.c:6938",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689152,
      "name": "addrconf_sysctl_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void addrconf_sysctl_unregister(struct inet6_dev * idev)
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
