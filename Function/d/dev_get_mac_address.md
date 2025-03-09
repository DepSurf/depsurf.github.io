# Function: <code>dev_get_mac_address</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589341104,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:8805",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589341104,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589237536,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:9064",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589237536,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962064,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:9054",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962064,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:8818",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581215,
      "name": "dev_get_mac_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071591477664,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593281968,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:8805",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593281968,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593746832,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:8813",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593746832,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```

```json
{
  "name": "dev_get_mac_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594525776,
      "name": "dev_get_mac_address",
      "external": true,
      "loc": "net/core/dev.c:8931",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594525776,
      "name": "dev_get_mac_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dev_get_mac_address(struct sockaddr * sa, struct net * net, char * dev_name)
```
</details>
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
