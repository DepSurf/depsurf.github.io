# Function: <code>alloc_etherdev_mqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447184,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:384",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447184,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586892944,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:385",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892944,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587087072,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:388",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087072,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587215774,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:388",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215632,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587730254,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:388",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730112,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588064584,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:388",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064416,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588240920,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:391",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240752,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631705,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:406",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631536,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588854073,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853904,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589737808,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:395",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589737808,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770912,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:395",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770912,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674448,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:396",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674448,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590431456,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:390",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590431456,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592031408,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:391",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592031408,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593847184,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:391",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593847184,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594221616,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:391",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/net_failover.c:net_failover_create",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594221616,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595018976,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:391",
      "file": "net/ethernet/eth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/net/net_failover.c:net_failover_create",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595018976,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502438100,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502437888,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235156600,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235156432,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295986212,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295985968,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278627072,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278626888,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460457,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460288,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588173145,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172976,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588792633,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792464,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct net_device * alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_etherdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588933257,
      "name": "alloc_etherdev_mqs",
      "external": true,
      "loc": "net/ethernet/eth.c:411",
      "file": "net/ethernet/eth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:netfront_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933088,
      "name": "alloc_etherdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
