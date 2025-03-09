# Function: <code>bpf_offload_dev_netdev_unregister</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807904,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:592",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807904,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901225,
      "name": "bpf_offload_dev_netdev_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580896432,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949696,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949696,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111392,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111392,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143024,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143024,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159808,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159808,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187536,
      "name": "bpf_offload_dev_netdev_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581397696,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962164,
      "name": "bpf_offload_dev_netdev_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581721968,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:625",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022601,
      "name": "bpf_offload_dev_netdev_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582128304,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326208,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:761",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326208,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487200,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:771",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487200,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492294352,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492294352,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1264
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226179220,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226179220,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1692
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285527648,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285527648,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1512
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272425524,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272425524,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918496,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918496,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864560,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864560,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909744,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909744,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967936,
      "name": "bpf_offload_dev_netdev_unregister",
      "external": true,
      "loc": "kernel/bpf/offload.c:628",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967936,
      "name": "bpf_offload_dev_netdev_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev * offdev, struct net_device * netdev)
```
</details>
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
