# Function: <code>ethtool_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586169718,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2671",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
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
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586589860,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2673",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
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
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586774420,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2720",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902960,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2770",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902960,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 989
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587394800,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2772",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394800,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695376,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2818",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695376,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587829296,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:2831",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829296,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131264,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3010",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131264,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588336400,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588336400,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589199808,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3124",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199808,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197696,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3118",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197696,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1422
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589090608,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3102",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090608,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501846528,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501846528,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2444
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295246976,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295246976,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2332
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943184,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943184,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587656288,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656288,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588274960,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274960,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```

```json
{
  "name": "ethtool_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588410256,
      "name": "ethtool_ioctl",
      "external": false,
      "loc": "net/socket.c:3090",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410256,
      "name": "ethtool_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
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
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ethtool_ioctl(struct net * net, struct compat_ifreq * ifr32)
```
</details>
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
