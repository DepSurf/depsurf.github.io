# Function: <code>bpf_offload_dev_netdev_register</code>

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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809056,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:559",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809056,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901263,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580897760,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954451,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580951008,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112624,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112624,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144256,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144256,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161024,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161024,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399008,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399008,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721072,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721072,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129744,
      "name": "bpf_offload_dev_netdev_register",
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
      "addr": 18446744071582129744,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324032,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:749",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324032,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484944,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:759",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484944,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492293440,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492293440,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226180912,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226180912,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285529520,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285529520,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1200
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272424438,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272424438,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923251,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580919808,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869315,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580865872,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914499,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580911056,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
```

```json
{
  "name": "bpf_offload_dev_netdev_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_offload_dev_netdev_register",
      "external": true,
      "loc": "kernel/bpf/offload.c:595",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974563,
      "name": "bpf_offload_dev_netdev_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580970224,
      "name": "bpf_offload_dev_netdev_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev * offdev, struct net_device * netdev)
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
