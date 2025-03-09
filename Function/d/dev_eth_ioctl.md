# Function: <code>dev_eth_ioctl</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_eth_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590185317,
      "name": "dev_eth_ioctl",
      "external": false,
      "loc": "net/core/dev_ioctl.c:243",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ifsioc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_eth_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591748771,
      "name": "dev_eth_ioctl",
      "external": false,
      "loc": "net/core/dev_ioctl.c:245",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ifsioc"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_eth_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593538857,
      "name": "dev_eth_ioctl",
      "external": false,
      "loc": "net/core/dev_ioctl.c:245",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ifsioc"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dev_eth_ioctl(struct net_device * dev, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_eth_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594006368,
      "name": "dev_eth_ioctl",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/dev_ioctl.c:dev_set_hwtstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594006368,
      "name": "dev_eth_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int dev_eth_ioctl(struct net_device * dev, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_eth_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594791808,
      "name": "dev_eth_ioctl",
      "external": false,
      "loc": "net/core/dev_ioctl.c:242",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/dev_ioctl.c:generic_hwtstamp_ioctl_lower",
        "net/core/dev_ioctl.c:dev_set_hwtstamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594791808,
      "name": "dev_eth_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int dev_eth_ioctl(struct net_device * dev, struct ifreq * ifr, unsigned int cmd)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
