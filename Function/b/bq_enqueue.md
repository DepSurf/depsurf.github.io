# Function: <code>bq_enqueue</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580615483,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:633",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580721354,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:316",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724775,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:599",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801502,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:317",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804910,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580889150,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:298",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893297,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580941790,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945937,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581101568,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:424",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071581108356,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:594",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101568,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581129056,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:410",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071581136756,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:696",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129056,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149744,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:403",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071581156721,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:659",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149744,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581384752,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:445",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071581394243,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:726",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384752,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581709534,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:446",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi"
      ]
    },
    {
      "addr": 18446744071581717646,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:728",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707952,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582114496,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:446",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071582124318,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:727",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114496,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582310576,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:443",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071582320590,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:748",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310576,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_prog * xdp_prog)
```

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471600,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:452",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue"
      ]
    },
    {
      "addr": 18446744071582481406,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:702",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471600,
      "name": "bq_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492283700,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492288632,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226171068,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3226175388,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285516400,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285522412,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272417256,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272421256,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580910590,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914737,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856654,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580860801,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580901838,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905985,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bq_enqueue",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580960574,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/devmap.c:436",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964737,
      "name": "bq_enqueue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bq_enqueue(struct net_device * dev, struct xdp_frame * xdpf, struct net_device * dev_rx)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog * xdp_prog</code>
</li>
</ul>
</details>
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
