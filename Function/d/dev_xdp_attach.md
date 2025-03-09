# Function: <code>dev_xdp_attach</code>

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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589332304,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9164",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332304,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589226960,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9423",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226960,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9414",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589966432,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1400
    },
    {
      "addr": 18446744071592697952,
      "name": "dev_xdp_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9152",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591512336,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2262
    },
    {
      "addr": 18446744071594584287,
      "name": "dev_xdp_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9139",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593286224,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2262
    },
    {
      "addr": 18446744071596323999,
      "name": "dev_xdp_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9147",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593741984,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2405
    },
    {
      "addr": 18446744071596853972,
      "name": "dev_xdp_attach.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
```

```json
{
  "name": "dev_xdp_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_attach",
      "external": false,
      "loc": "net/core/dev.c:9265",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594520384,
      "name": "dev_xdp_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
    },
    {
      "addr": 18446744071597778942,
      "name": "dev_xdp_attach.cold",
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dev_xdp_attach(struct net_device * dev, struct netlink_ext_ack * extack, struct bpf_xdp_link * link, struct bpf_prog * new_prog, struct bpf_prog * old_prog, u32 flags)
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
